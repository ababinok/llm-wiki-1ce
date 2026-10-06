# Подключение AMQP-систем

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/amqp-connection/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/amqp-connection/index.html
> SHA256: 1fceb6a6b746104e7f5d327ac0053e392950cab69fc2bf6089513b3fbdf05970
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Чтобы отправлять и получать сообщения, внешние системы должны подключиться к серверу «1С:Предприятие.Элемента» по протоколу AMQP версии 1.0. Для этого предназначены узлы процесса интеграции вида [Канал1СИсточник](../../wiki/integration/channel-1c-source-ddb853b7d45d.md) и [Канал1СНазначение](../../wiki/integration/channel-1c-destination-3c02e5ef031f.md). Порт брокера сервера «1С:Предприятие.Элемента» и имя очереди для подключения вы можете узнать при помощи [HTTP-сервиса описания](../../wiki/project/get-channel-description-43bbb37d590c.md) «1С:Предприятие.Элемента».

> [!NOTE] дополнительно
> При отправке сообщения может быть определен перечень информационных систем, которым это сообщение адресовано. Для этого следует задать в значении заголовка AMQP-сообщения с именем **RecipientCode** строку, содержащую коды справочника информационных систем, разделенные запятой `,`. Если информационные системы явно не указаны, сообщение будет направлено всем возможным информационным системам.

## Аутентификация

При подключении к серверу клиентское приложение должно пройти процедуру аутентификации.

Отправьте запрос на получение билета (token) аутентификации на сервер по адресу:

```text
http://serverhost:port/auth/oidc/token
```

где `serverhost:port` имя хоста и порт, определенные в конфигурационном файле [**server.yaml**](https://1cmycloud.com/console/help/element/10.0/docs/topics/server-connection-settings-file/).

Формат запроса:

```text
POST /auth/oidc/token
Content-Type: application/x-www-form-urlencoded
Authorization: Basic <ClientId:ClientSecret в кодировке Base64>
grant_type=CLIENT_CREDENTIALS
```

В качестве `ClientId` и `ClientSecret` следует указать идентификатор и секрет клиента, полученные при создании информационных систем в приложении «1С:Предприятие.Элемент» (**Приложение** ⟶ **Инфосистемы** ⟶ **Выдать ключ API**).

Пример:

```xbsl
пер ИдентификаторКлиента = "1_e1NvnB33xjB7IrZCqJT2WHOyR0Ew58vedLLQxXwE="
пер СекретКлиента = "zd9QHBC_D9Jmurubko7xB97eJqCAQjJk5lNYp7Ny4s4="
пер СтрокаBase64 = Кодировки.Base64.КодироватьВСтроку(ИдентификаторКлиента + ":" + СекретКлиента)

СтрокаBase64 = СтрокаBase64.Заменить(Символы.НОВАЯ_СТРОКА, "", Ложь)
СтрокаBase64 = СтрокаBase64.Заменить(Символы.ВОЗВРАТ_КАРЕТКИ, "", Ложь)

пер Заголовки = новый ЗаголовкиHttp()
Заголовки.Добавить("Content-Type", "application/x-www-form-urlencoded")
Заголовки.Добавить("Authorization", "Basic $СтрокаBase64")

пер Запрос = КлиентHttp.ЗапросGet("/auth/oidc/token")
Запрос.ДобавитьЗаголовки(Заголовки)
Запрос.УстановитьТело("grant_type=client_credentials")
```

Пример **cURL**:

```text
curl --request POST \
  --url http://localhost:9090/auth/oidc/token \
  -u 1_e1NvnB33xjB7IrZCqJT2WHOyR0Ew58vedLLQxXwE=:zd9QHBC_D9Jmurubko7xB97eJqCAQjJk5lNYp7Ny4s4= \
  --header "content-type: application/x-www-form-urlencoded" \
  --data grant_type=client_credentials
```

Пример **Python**:

```python
import requests
import base64

url = 'http://localhost:9090/auth/oidc/token'
id = '1_e1NvnB33xjB7IrZCqJT2WHOyR0Ew58vedLLQxXwE='
secret = 'zd9QHBC_D9Jmurubko7xB97eJqCAQjJk5lNYp7Ny4s4='
qry = '{id}:{secret}'.format(id=id, secret=secret)
basicAuthKey = base64.b64encode(str.encode(qry)).decode('ascii')
headers = {
    'Authorization': 'Basic {}'.format(basicAuthKey),
    'Content-Type': 'application/x-www-form-urlencoded'
}
resp = requests.post(url, headers=headers, data='grant_type=client_credentials')
if (not resp.ok):
    print('Auth error: ' + resp.reason)
    exit(1)
authToken = resp.json()['id_token']
```

В случае успешного получения билета, вы получите ответ в формате JSON:

```json
{
  "access_token" : "Not implemented",
  "id_token" : "БИЛЕТ",
  "token_type" : "Bearer"
}
```

Полученный билет должен использоваться при подключении к брокеру сервера «1С:Предприятие.Элемента» по протоколу AMQP, а также при вызове HTTP и SOAP-сервисов «Элемента»:

- При подключении к брокеру сервера билет указывается в качестве имени и пароля при подключении.
- При вызове HTTP и SOAP-сервисов билет указывается в заголовке **Authorization** в форме:
  
  ```text
  Authorization: Bearer БИЛЕТ
  ```

Билет действителен в течение часа, поэтому если нужно сделать сразу несколько вызовов (возможно, разных сервисов), то можно использовать уже полученный билет, не вызывая снова менеджер аутентификации.

Если билет устарел, то при вызове сервиса вернется ответ с кодом 401. Это значит, что нужно снова запросить билет у менеджера аутентификации. При попытке подключиться к брокеру сервера с устаревшим билетом будет получена ошибка аутентификации.


Дополнительная информация. [Описание иллюстрации](../figures/44359ba82128f5d7089432790b2dab0b9e062428196eb046108b113134bfe244-63e45aa5a805c2ac.md)
