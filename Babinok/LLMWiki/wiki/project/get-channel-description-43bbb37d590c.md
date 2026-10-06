# Получение описания каналов и порта брокера

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [get-channel-description-43bbb37d590c-4b851f9c3176ad13](../../raw/text-10.0/get-channel-description-43bbb37d590c-4b851f9c3176ad13.md); [44359ba82128f5d7089432790b2dab0b9e062428196eb046108b113134bfe244-63e45aa5a805c2ac](../../raw/figures/44359ba82128f5d7089432790b2dab0b9e062428196eb046108b113134bfe244-63e45aa5a805c2ac.md); [71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d](../../raw/figures/71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Получение описания каналов и порта брокера`, `get-channel-description`.

## Обзор

В «1С:Предприятие.Элементе» есть HTTP-сервис описания каналов процесса интеграции.

## Документированный контракт и примеры

В «1С:Предприятие.Элементе» есть HTTP-сервис описания каналов процесса интеграции. Это специализированный сервис, который возвращает авторизованной информационной системе JSON-ответ, содержащий список экземпляров каналов, к которым эта информационная система имеет доступ, а также информацию по каждому из них. С помощью этого сервиса также можно получить порт брокера сообщений и имя очередей для подключения систем по протоколу AMQP.

> [!NOTE] дополнительно
> Чтобы использовать HTTP-сервисы описания «1С:Предприятие.Элемента», вам необходимо [пройти аутентификацию](../integration/amqp-connection-3210085a03a8.md) и получить билет. Этот билет следует использовать в заголовке **Authorization** при каждом запросе.

## Метод metadata

Метод GET. Формат вызова:

```text
/sys/esb/metadata/channels
```

Возвращает авторизованной информационной системе описание каналов «Элемента» времени редактирования.

Структура элемента списка:

- **process**
  
  Имя процесса интеграции в проекте
  
  > [!WARNING] важно
  > В качестве имени процесса интеграции передается значение свойства [«Имя процесса для внешнего сервиса интеграции 1С:Предприятие»](../integration/integration-process-properties-882a1d3da233.md).
- **processDescription**
  
  Описание процесса интеграции, заданное в схеме
- **channel**
  
  Логическое имя канала, заданное в схеме процесса интеграции
- **channelDescription**
  
  Описание канала, заданное в схеме процесса интеграции
- **access**
  
  Разрешена ли отправка сообщений в канал (**WRITE_ONLY**) или получение из канала (**READ_ONLY**)

Пример запроса (**cURL**):

```text
curl --request GET \
    --url http://localhost:9090/applications/My-Application/sys/esb/metadata/channels \
    --header "authorization: Bearer БИЛЕТ"
```

Пример результата:

```json
 [ {
  "process" : "e1c::ТестовыйПроект::Основной::OfficeToShop",
  "processDescription" : "One Office to One Shop",
  "channel" : "toShop",
  "channelDescription" : "shop incoming",
  "sendAllowed" : "READ_ONLY"

}, {
  "process" : "e1c::ТестовыйПроект::Основной::OfficeToShop",
  "processDescription" : "One Office to One Shop",
  "channel" : "toOffice",
  "channelDescription" : "office incoming",
  "sendAllowed" : "READ_ONLY"
}, {
  "process" : "e1c::ТестовыйПроект::Основной::OfficeToShop",
  "processDescription" : "One Office to One Shop",
  "channel" : "fromShop",
  "channelDescription" : "shop outgoing",
  "sendAllowed" : "WRITE_ONLY"
}, {
  "process" : "e1c::ТестовыйПроект::Основной::OfficeToShop",
  "processDescription" : null,
  "channel" : "fromOffice",
  "channelDescription" : null,
  "sendAllowed" : "WRITE_ONLY"

} ]
```

## Метод runtime

Метод GET. Формат вызова:

```text
/sys/esb/runtime/channels
```

Возвращает аутентифицированной информационной системе описание каналов «Элемента» времени исполнения, которые этой информационной системе доступны.

Структура элемента списка:

- **process**
  
  Имя процесса интеграции в проекте
  
  > [!WARNING] важно
  > В качестве имени процесса интеграции передается значение свойства [«Имя процесса для внешнего сервиса интеграции 1С:Предприятие»](../integration/integration-process-properties-882a1d3da233.md).
- **channel**
  
  Логическое имя канала, заданное в схеме процесса интеграции
- **destination**
  
  Идентификатор канала (имя очереди для подключения)
- **port**
  
  Порт брокера сервера «1С:Предприятие.Элемента»

Пример запроса (**cURL**):

```text
curl --request GET \
   --url http://localhost:9090/applications/My-Application/sys/esb/runtime/channels \
   --header "authorization: Bearer БИЛЕТ"
```

Пример результата:

```json
{
  "items" : [ {
    "process" : "e1c::ТестовыйПроект::Основной::OfficeToShop",
    "channel" : "toShop",
    "destination" : "PUBLIC.VGVzdEFwcA==.-1.d34871f503c14792bd069cfde7e2caa8.toShop.shop"
  }, {
    "process" : "e1c::ТестовыйПроект::Основной::OfficeToShop",
    "channel" : "fromShop",
    "destination" : "PUBLIC.VGVzdEFwcA==.-1.d34871f503c14792bd069cfde7e2caa8.fromShop.shop"
  } ],
  "port" : 6698
}
```


Дополнительная информация. [Описание иллюстрации](../../raw/figures/44359ba82128f5d7089432790b2dab0b9e062428196eb046108b113134bfe244-63e45aa5a805c2ac.md)


Важно. [Описание иллюстрации](../../raw/figures/71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d.md)

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Получение описания каналов и порта брокера](https://1cmycloud.com/console/help/element/10.0/docs/topics/get-channel-description/).
