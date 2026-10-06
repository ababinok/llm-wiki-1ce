# Журнал сервера

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [server-event-log-7ac20e69de17-fd1ddb0bcb88d108](../../raw/text-10.0/server-event-log-7ac20e69de17-fd1ddb0bcb88d108.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Журнал сервера`, `server-event-log`.

## Обзор

Журнал событий сервера — это инструмент службы технической поддержки фирмы «1С».

## Документированный контракт и примеры

Журнал событий сервера — это инструмент службы технической поддержки фирмы «1С». Он помогает расследовать ошибки, возникающие в процессе работы «1С:Предприятие.Элемента». Также этот журнал могут использовать подготовленные специалисты, занимающиеся крупными внедрениями.

В этот журнал записываются события получения и отправки сообщений.

Все журналы сервера настраиваются в файле [logging.yml](https://1cmycloud.com/console/help/element/10.0/docs/topics/server-log-file/). Журнал событий стандартно размещается в следующих каталогах:

- Windows
- Linux

```text
C:\ProgramData\1C\1CE\instances\1c-enterprise-element-server-with-ide
```

Примеры сообщений, подтверждающих передачу сообщений в информационную базу получателя:

```text
2020/05/09-13:53:36.958-0,JAVA,0,level=INFO,pid=10192,threadId=171,thread=appmanager-internal-long-operations-1,logger=ESB,message='Integration bus serv2020/05/09-19:50:54.250-0,JAVA,0,level=INFO,pid=4328,threadId=293,thread=Camel (camel-1) thread #3 - RecipientList,logger=ESB,message=Message ID:e91b8c90-ab57-1eb4-8cc9-e3ab2eabf56d delivered to Processes::СетьМагазинов.ВМагазин..shop
2020/05/09-20:00:05.428-0,JAVA,0,level=INFO,pid=4328,threadId=343,thread=Camel (camel-1) thread #5 - RecipientList,logger=ESB,message=Message ID:bbaa94a4-b37a-19cf-bc09-d4223e7506ff delivered to Processes::СетьМагазинов.ВОфис..office
```

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Журнал сервера](https://1cmycloud.com/console/help/element/10.0/docs/topics/server-event-log/).
