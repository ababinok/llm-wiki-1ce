# Закрываемое

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [closeable-ru-67cd73fca69d-3c40e11e1bda5608](../../raw/text-10.0/closeable-ru-67cd73fca69d-3c40e11e1bda5608.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std.

Имена для поиска: `Закрываемое`, `Closeable`, `Стд::Закрываемое`, `Std::Closeable`.

## Обзор

Базовый тип для объектов, удерживающих системные ресурсы (порты, файлы, и т.

## Документированный контракт и примеры

`Стд::Закрываемое` `Доступность: КлиентИСервер`

Базовый тип для объектов, удерживающих системные ресурсы (порты, файлы, и т. д.) и контекстов. Закрытие выполняется автоматически, но через неопределенное время после того, как объект перестал быть достижимым. Предполагает использование модификатора `исп` при объявлении переменных, для контроля момента закрытия объекта.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

*Дочерние типы:* [АдминистрированиеСервераV8](v8serveradministration-ru-449df116c8d6.md), [ВыборкаДанных](dataselection-ru-03b255730e2a.md), [ДокументPdf](../data/pdfdocument-ru-0f22a31f119f.md), [КаталогПочтыImap](../integration/imapemaildirectory-ru-8ee78c630c1f.md), [КонсольSsh](../integration/sshconsole-ru-fb1484066c70.md), [Контекст](context-ru-aa03c6bdd5aa.md), [МониторФайловойСистемы](filesystemmonitor-ru-208295a1f6e7.md), [ОтветHttp](../integration/httpresponse-ru-8fa5b68112a5.md), [ПотокЗаписи](writablestream-ru-db9a09ef1933.md), [ПотокЧтения](readablestream-ru-c306ee00c3af.md), [РезультатВыборкиSql](../data/sqlselectresult-ru-b351439e205b.md), [РезультатВызоваПроцедурыSql](../data/sqlprocedurecallresult-ru-32a7cafaceba.md), [РезультатЗапроса](../queries/queryresult-ru-5ca8e0f9453c.md), [РезультатПоискаСобытийЖурналаСобытий](eventlogeventsearchresult-ru-2dbf991487f4.md), [РезультатЧтенияДанных](readdataresult-ru-cb902b234ec0.md), [СоединениеFtp](ftpconnection-ru-57c94d7252fd.md), [СоединениеImap](../integration/imapconnection-ru-0dd095a80a93.md), [СоединениеPop3](pop3connection-ru-724b8596bdb3.md), [СоединениеSftp](../integration/sftpconnection-ru-08f1490aa3e3.md), [СоединениеSql](../data/sqlconnection-ru-c5e86d40a6b0.md), [СоединениеSsh](../integration/sshconnection-ru-ddf18cfbb82f.md)

---

## Методы

### Закрыть

`Доступность: КлиентИСервер`

```
Закрыть()
```

Закрывает объект, освобождая выделенные ресурсы. Повторный вызов метода не выполняет никаких действий.

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд — Пространство имён XBSL: Std](std-c15458c2f5f0.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [Закрываемое](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Closeable_ru/).
