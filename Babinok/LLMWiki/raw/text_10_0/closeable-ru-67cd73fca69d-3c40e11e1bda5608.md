# Закрываемое

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Closeable_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Closeable_ru/index.html
> SHA256: 1a89585ef043c406a6514b1a7c9d6beac04eec69173b2b814b19e429a0def8f7
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Закрываемое` `Доступность: КлиентИСервер`

Базовый тип для объектов, удерживающих системные ресурсы (порты, файлы, и т. д.) и контекстов. Закрытие выполняется автоматически, но через неопределенное время после того, как объект перестал быть достижимым. Предполагает использование модификатора `исп` при объявлении переменных, для контроля момента закрытия объекта.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [АдминистрированиеСервераV8](../../wiki/stdlib/v8serveradministration-ru-449df116c8d6.md), [ВыборкаДанных](../../wiki/stdlib/dataselection-ru-03b255730e2a.md), [ДокументPdf](../../wiki/data/pdfdocument-ru-0f22a31f119f.md), [КаталогПочтыImap](../../wiki/integration/imapemaildirectory-ru-8ee78c630c1f.md), [КонсольSsh](../../wiki/integration/sshconsole-ru-fb1484066c70.md), [Контекст](../../wiki/stdlib/context-ru-aa03c6bdd5aa.md), [МониторФайловойСистемы](../../wiki/stdlib/filesystemmonitor-ru-208295a1f6e7.md), [ОтветHttp](../../wiki/integration/httpresponse-ru-8fa5b68112a5.md), [ПотокЗаписи](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md), [ПотокЧтения](../../wiki/stdlib/readablestream-ru-c306ee00c3af.md), [РезультатВыборкиSql](../../wiki/data/sqlselectresult-ru-b351439e205b.md), [РезультатВызоваПроцедурыSql](../../wiki/data/sqlprocedurecallresult-ru-32a7cafaceba.md), [РезультатЗапроса](../../wiki/queries/queryresult-ru-5ca8e0f9453c.md), [РезультатПоискаСобытийЖурналаСобытий](../../wiki/stdlib/eventlogeventsearchresult-ru-2dbf991487f4.md), [РезультатЧтенияДанных](../../wiki/stdlib/readdataresult-ru-cb902b234ec0.md), [СоединениеFtp](../../wiki/stdlib/ftpconnection-ru-57c94d7252fd.md), [СоединениеImap](../../wiki/integration/imapconnection-ru-0dd095a80a93.md), [СоединениеPop3](../../wiki/stdlib/pop3connection-ru-724b8596bdb3.md), [СоединениеSftp](../../wiki/integration/sftpconnection-ru-08f1490aa3e3.md), [СоединениеSql](../../wiki/data/sqlconnection-ru-c5e86d40a6b0.md), [СоединениеSsh](../../wiki/integration/sshconnection-ru-ddf18cfbb82f.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
