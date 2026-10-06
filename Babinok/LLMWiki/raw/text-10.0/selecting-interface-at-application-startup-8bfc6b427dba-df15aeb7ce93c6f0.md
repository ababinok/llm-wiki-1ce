# Выбор интерфейса при запуске приложения

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/selecting-interface-at-application-startup/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/selecting-interface-at-application-startup/index.html
> SHA256: a1b10371dccb8e2aac7f677f52e52dcdf93b44744d48c3cf4b51affc209afb81
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Веб-клиент при запуске ищет в проекте компонент, унаследованный от компонентов [СтандартноеКлиентскоеПриложениеСРазделами](../../wiki/interface/standard-client-application-with-sections-component-49da52beb720.md) или [ПроизвольноеКлиентскоеПриложение](../../wiki/interface/custom-client-application-component-a5e093d01cdd.md) и запускает его экземпляр.

Одно и то же приложение может иметь несколько интерфейсов. Для этого используйте перечисленные компоненты с разными значениями свойства **Путь**.

Стандартное значение свойства **Путь** — пустая строка. Это значит, что вход в приложение выполняется по адресу публикации проекта.

Во втором компоненте, описывающем клиентское приложение, вы можете установить, например, **Путь** равным **back-office**, и тогда ваше приложение **myAPP**, например, будет иметь два интерфейса по следующим адресам:

- [https://server.example.com/applications/myAPP](https://server.example.com/applications/myAPP)
- [https://server.example.com/applications/myAPP/back-office](https://server.example.com/applications/myAPP/back-office)
