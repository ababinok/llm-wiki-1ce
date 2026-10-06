# Пример 3. Настройка обмена сообщениями между информационными базами «Офис» и «Магазин»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/esb-demo-example-3/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/esb-demo-example-3/index.html
> SHA256: a65dd0ed857fb34414807e52788c8ab189693de81a4ca98de3c472fc9e23c426
> SnapshotCreated: 2026-10-05
> Rendition: verified text

> [!WARNING] важно
> Процессы интеграции недоступны в облачной версии «1С:Предприятие.Элемента».

> [!TIP] совет
> В данном примере используется демонстрационная конфигурация информационной базы «Офис» ([скачать](https://doc-files.1cmycloud.com/downloads?state=esb/office_template.cf)) и «Магазин» ([скачать](https://doc-files.1cmycloud.com/downloads?state=esb/shop_template.cf)).

Пример показывает организацию взаимодействия между двумя информационными базами системы «1С:Предприятие» — **Офис** и **Магазин**:

- Офис запрашивает в магазине информацию об остатках товаров.
- Магазин получает запрос и отправляет в ответ отчет по остаткам.
- Офис получает ответ и сохраняет его в информационной базе.

В ходе этого примера вы:

- В среде разработки:
  
  - [Создадите](../../wiki/project/example-3-create-project-e939e343a8f8.md)
    
    проект и настроите в нем процесс интеграции.
- На сервере:
  
  - [Создадите и настроите](../../wiki/project/example-3-create-information-systems-6671f6c1c47c.md)
    
    информационные системы.
- [Создадите](../../wiki/project/example-3-create-infobases-709c86fa51af.md)
  
  демонстрационные базы «1С:Предприятия» и в каждой из этих баз:
  
  - [Добавите](../../wiki/integration/example-3-add-integration-service-48b05ad57a49.md)
    
    сервис интеграции.
  - [Загрузите](../../wiki/integration/example-3-load-channel-982f3344ae15.md)
    
    в него информацию о доступных каналах.
  - [Напишете](../../wiki/project/example-3-information-system-code-4a99225f6504.md)
    
    код обмена сообщениями.
  - [Добавите](../../wiki/project/example-3-create-scheduled-job-9a9790cae4c1.md)
    
    регламентное задание для обмена сообщениями с
    
    «1С:Предприятие.Элементом»
    
    .
  - [Настроите](../../wiki/project/example-3-connect-infobases-to-server-6a89383c2ca7.md)
    
    подключение к серверу.
- [Проверите](../../wiki/integration/example-3-test-message-exchange-6d3a2ac14e30.md)
  
  обмен сообщениями.

## См. также

- [Свойства узла процесса интеграции вида «Канал1СИсточник»](../../wiki/integration/channel-1c-source-ddb853b7d45d.md)
- [Свойства узла процесса интеграции вида «Канал1СНазначение»](../../wiki/integration/channel-1c-destination-3c02e5ef031f.md)


Важно. [Описание иллюстрации](../figures/71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d.md)


Совет. [Описание иллюстрации](../figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md)
