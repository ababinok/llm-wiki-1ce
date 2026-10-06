# Выбор интерфейса при запуске приложения

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [selecting-interface-at-application-startup-8bfc6b427dba-df15aeb7ce93c6f0](../../raw/text-10.0/selecting-interface-at-application-startup-8bfc6b427dba-df15aeb7ce93c6f0.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Выбор интерфейса при запуске приложения`, `selecting-interface-at-application-startup`.

## Обзор

Веб-клиент при запуске ищет в проекте компонент, унаследованный от компонентов [СтандартноеКлиентскоеПриложениеСРазделами](standard-client-application-with-sections-component-49da52beb720.md) или [ПроизвольноеКлиентскоеПриложение](custom-client-application-component-a5e093d01cdd.md) и запускает его экземпляр.

## Документированный контракт и примеры

Веб-клиент при запуске ищет в проекте компонент, унаследованный от компонентов [СтандартноеКлиентскоеПриложениеСРазделами](standard-client-application-with-sections-component-49da52beb720.md) или [ПроизвольноеКлиентскоеПриложение](custom-client-application-component-a5e093d01cdd.md) и запускает его экземпляр.

Одно и то же приложение может иметь несколько интерфейсов. Для этого используйте перечисленные компоненты с разными значениями свойства **Путь**.

Стандартное значение свойства **Путь** — пустая строка. Это значит, что вход в приложение выполняется по адресу публикации проекта.

Во втором компоненте, описывающем клиентское приложение, вы можете установить, например, **Путь** равным **back-office**, и тогда ваше приложение **myAPP**, например, будет иметь два интерфейса по следующим адресам:

- [https://server.example.com/applications/myAPP](https://server.example.com/applications/myAPP)
- [https://server.example.com/applications/myAPP/back-office](https://server.example.com/applications/myAPP/back-office)

## See Also

- [Навигатор раздела](overview.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [Выбор интерфейса при запуске приложения](https://1cmycloud.com/console/help/element/10.0/docs/topics/selecting-interface-at-application-startup/).
