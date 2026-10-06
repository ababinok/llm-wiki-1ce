# Исключение

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Exception_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Exception_ru/index.html
> SHA256: a61930d42f4ffbcf8c1f5fe979b071824b72cb304e15677d3425eeb0eb406e3f
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Исключение` `Доступность: КлиентИСервер`

Базовый тип любого исключения. Объекты данного типа можно выбросить с помощью инструкции `выбросить` и перехватывать в секции `поймать` блока `попытка`.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИсключениеFtp](../../wiki/stdlib/ftpexception-ru-132dadd916c0.md), [ИсключениеHttp](../../wiki/integration/httpexception-ru-2140341cd0ec.md), [ИсключениеPaas](../../wiki/stdlib/paasexception-ru-58e007c03606.md), [ИсключениеPdf](../../wiki/stdlib/pdfexception-ru-fca07efa7071.md), [ИсключениеSftp](../../wiki/integration/sftpexception-ru-b1502c5e1bd8.md), [ИсключениеSql](../../wiki/data/sqlexception-ru-c108d8de1746.md), [ИсключениеSsh](../../wiki/integration/sshexception-ru-96483eea9a34.md), [ИсключениеАдминистрированияКластера](../../wiki/stdlib/administrationclusterexception-ru-a77ecbabe797.md), [ИсключениеАрифметики](../../wiki/stdlib/arithmeticexception-ru-fd5e53d78c0b.md), [ИсключениеБезопасногоХранилища](../../wiki/interface/securestorageexception-ru-2e9de5b75101.md), [ИсключениеБуфераОбмена](../../wiki/interface/clipboardexception-ru-60397212f434.md), [ИсключениеВалидации](../../wiki/stdlib/validationexception-ru-e71e5b661e18.md), [ИсключениеВводаВывода](../../wiki/stdlib/inputoutputexception-ru-ceba5f672999.md), [ИсключениеВерификацииПользователя](../../wiki/interface/userverificationexception-ru-b18aa1737905.md), [ИсключениеВзаимоблокировка](../../wiki/stdlib/deadlockexception-ru-c6366ebdf84e.md), [ИсключениеВнутренняяОшибкаВыполненияЗадания](../../wiki/stdlib/jobexecutioninternalerrorexception-ru-881eb62ccbab.md), [ИсключениеВызоваSoapСервиса](../../wiki/integration/soapservicecallexception-ru-928205adb79d.md), [ИсключениеВызоваСобытия](../../wiki/interface/eventcallexception-ru-b0fcb44ab497.md), [ИсключениеВыполненияJs](../../wiki/interface/jsexecutionexception-ru-436350b62184.md), [ИсключениеВыполнения](../../wiki/stdlib/executionexception-ru-98406726cb92.md), [ИсключениеГенерацииQrКода](../../wiki/stdlib/qrcodegenerationexception-ru-cb199f61d719.md), [ИсключениеГеозон](../../wiki/stdlib/geofenceexception-ru-19cbe9afb179.md), [ИсключениеДвоичногоОбъекта](../../wiki/data/binaryobjectexception-ru-ccf2a7416223.md), [ИсключениеДинамическогоВыполнения](../../wiki/stdlib/dynamicexecutionexception-ru-30d60771d2af.md), [ИсключениеДокументаHtml](../../wiki/data/htmldocumentexception-ru-6ea628ca38f8.md), [ИсключениеДоставляемыхУведомлений](../../wiki/stdlib/deliverablenotificationexception-ru-cbf2a39d4997.md), [ИсключениеДоступЗапрещен](../../wiki/stdlib/accessdeniedexception-ru-f679f509f3e4.md), [ИсключениеДоступаКСекрету](../../wiki/security/secretaccessexception-ru-b71fa04e142e.md), [ИсключениеДоступаКСредеИсполнения](../../wiki/security/executionenvironmentpermissionexception-ru-7a816a1b673d.md), [ИсключениеДоступаКФайлу](../../wiki/security/filepermissionexception-ru-c4b7f0af5ac2.md), [ИсключениеЗагрузкаФайлаОтменена](../../wiki/interface/fileuploadcanceledexception-ru-547f1577d835.md), [ИсключениеЗагрузкиДвоичногоОбъекта](../../wiki/data/binaryobjectuploadexception-ru-f7b277993953.md), [ИсключениеЗаданиеОтменено](../../wiki/stdlib/jobcanceledexception-ru-85ca9a9057fc.md), [ИсключениеЗаписиJson](../../wiki/integration/jsonwriterexception-ru-9073a0c1344f.md), [ИсключениеЗаписиXml](../../wiki/integration/xmlwriterexception-ru-a4b2974dbea2.md), [ИсключениеЗаписьНеМожетБытьИзменена](../../wiki/stdlib/recordcannotbeupdatedexception-ru-7451959e658a.md), [ИсключениеЗаписьНеМожетБытьУдалена](../../wiki/stdlib/recordcannotbedeletedexception-ru-55e7aeddc198.md), [ИсключениеЗаписьНеУникальна](../../wiki/stdlib/recordnotuniqueexception-ru-ac3c448c69da.md), [ИсключениеЗапроса](../../wiki/queries/queryexception-ru-aa570351115a.md), [ИсключениеЗначениеСвойстваНеУникально](../../wiki/stdlib/propertyvaluenotuniqueexception-ru-ad124b3a4ec2.md), [ИсключениеИндексВнеГраниц](../../wiki/stdlib/indexoutofboundsexception-ru-2b34a623369c.md), [ИсключениеИнтеграционнойШины](../../wiki/integration/integrationbusexception-ru-0bbe235ac154.md), [ИсключениеИсточникКопированияСущностиНеСуществует](../../wiki/data/entitycopysourcenotexistsexception-ru-ccae6b569bee.md), [ИсключениеКомпиляции](../../wiki/stdlib/compileexception-ru-579bf6b6839e.md), [ИсключениеКомпонентНеГотов](../../wiki/interface/componentnotreadyexception-ru-8f818b439334.md), [ИсключениеКриптографии](../../wiki/stdlib/cryptoexception-ru-9269fbee8009.md), [ИсключениеМультимедиа](../../wiki/interface/multimediaexception-ru-9913f65f68cd.md), [ИсключениеНедопустимоеСостояние](../../wiki/stdlib/illegalstateexception-ru-4c1cc853b874.md), [ИсключениеНедопустимоеСостояниеТранзакции](../../wiki/data/illegaltransactionstateexception-ru-eb3ecacffa4d.md), [ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md), [ИсключениеНедопустимыйФормат](../../wiki/stdlib/illegalformatexception-ru-8ff587175d1a.md), [ИсключениеНекорректноеРегулярноеВыражение](../../wiki/stdlib/illegalregularexpressionexception-ru-b4ae057eb659.md), [ИсключениеНеподдерживаемаяОперация](../../wiki/stdlib/unsupportedoperationexception-ru-6fc50eac7766.md), [ИсключениеНесоответствияВладельцевИерархии](../../wiki/stdlib/hierarchyownersmismatchexception-ru-0887bade9def.md), [ИсключениеНумерации](../../wiki/stdlib/numberingexception-ru-5d3b90192a0f.md), [ИсключениеОбработчикФоновогоЗаданияНеНайден](../../wiki/stdlib/backgroundjobhandlernotfoundexception-ru-1bdcdb876ba3.md), [ИсключениеОдновременноеИзменениеСущности](../../wiki/data/concurrententitymodificationexception-ru-0b6f275abc3d.md), [ИсключениеОтражения](../../wiki/stdlib/reflectionexception-ru-eaf98f596473.md), [ИсключениеПапкаИзбранногоПользователяНеСуществует](../../wiki/interface/userfavoritesfoldernotexistsexception-ru-617124f37903.md), [ИсключениеПапкаИзбранногоПользователяНеУникальна](../../wiki/interface/userfavoritesfoldernotuniqueexception-ru-3b54669191b2.md), [ИсключениеПараметрыРаботыКлиентаНеИнициализированы](../../wiki/interface/clientworkparametersnotinitializedexception-ru-852da47af9f8.md), [ИсключениеПоискаXPath](../../wiki/integration/xpathsearchexception-ru-680675674c5a.md), [ИсключениеПоискаСущности](../../wiki/data/entitysearchexception-ru-ae3d905c5b5f.md), [ИсключениеПолнотекстовогоПоиска](../../wiki/stdlib/fulltextsearchexception-ru-b26a54521aae.md), [ИсключениеПостроенияXmlDom](../../wiki/integration/xmldombuildexception-ru-18c59d9ac500.md), [ИсключениеПостроенияГеографическогоМаршрута](../../wiki/stdlib/geographicroutebuildingexception-ru-62c291947120.md), [ИсключениеПочты](../../wiki/stdlib/emailexception-ru-daee01e8e961.md), [ИсключениеПреобразованияXml](../../wiki/integration/xmltransformationexception-ru-6f9c954f3882.md), [ИсключениеПриглашенияЕдиногоМобильногоКлиента](../../wiki/stdlib/unifiedmobileclientinvitationexception-ru-57368b91aad6.md), [ИсключениеПроверкиXml](../../wiki/integration/xmlvalidationexception-ru-52055d7c2301.md), [ИсключениеПроверкиТипа](../../wiki/stdlib/typecheckexception-ru-d4c24f2f9eee.md), [ИсключениеРазрешениеОтсутствует](../../wiki/security/nopermissionexception-ru-1f930860881b.md), [ИсключениеРесурсНеНайден](../../wiki/stdlib/resourcenotfoundexception-ru-9455193031c3.md), [ИсключениеСервера](../../wiki/interface/serverexception-ru-c5830d7da0f3.md), [ИсключениеСистемыВзаимодействия](../../wiki/integration/collaborationsystemexception-ru-f8d82f9023f2.md), [ИсключениеСравнения](../../wiki/stdlib/compareexception-ru-66603110ce3a.md), [ИсключениеСсылкаНеУникальна](../../wiki/stdlib/referencenotuniqueexception-ru-e8aba27ec85c.md), [ИсключениеСущностьНеЗаписана](../../wiki/data/entitynotwrittenexception-ru-bf648734c903.md), [ИсключениеТабличногоДокумента](../../wiki/stdlib/spreadsheetexception-ru-5cca8ccd5cbf.md), [ИсключениеТаймаутаБлокировки](../../wiki/stdlib/locktimeoutexception-ru-944ade356519.md), [ИсключениеТаймаутаЗадания](../../wiki/stdlib/jobtimeoutexception-ru-84b1e550fa23.md), [ИсключениеУправленияПользователями](../../wiki/stdlib/usermanagementexception-ru-9741246a36bd.md), [ИсключениеФайловойСистемы](../../wiki/stdlib/filesystemexception-ru-fd95df425388.md), [ИсключениеХешированияДанных](../../wiki/stdlib/datahashingexception-ru-11502d9b8867.md), [ИсключениеЦиклВИерархии](../../wiki/stdlib/cycleinhierarchyexception-ru-1a6ef43231a5.md), [ИсключениеЧтенияJson](../../wiki/integration/jsonreaderexception-ru-62be4dbb30ff.md), [ИсключениеЧтенияXml](../../wiki/integration/xmlreaderexception-ru-0d8061eee533.md), [ИсключениеЧтенияДанных](../../wiki/stdlib/datareadexception-ru-8323ffdb9fa5.md), [ИсключениеЭкспортаОтчета](../../wiki/stdlib/reportexportexception-ru-a8fa5d8929ac.md), [ИсключениеЭлементИзбранногоПользователяНеСуществует](../../wiki/interface/userfavoritesitemnotexistsexception-ru-b3339fa55f53.md), [ИсключениеЭлементИзбранногоПользователяНеУникален](../../wiki/interface/userfavoritesitemnotuniqueexception-ru-4d9fae2391ac.md)

---

## Свойства

### Ид

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Ид: Строка
```

Идентификатор исключения.

---

### Описание

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Описание: Строка
```

Строковое описание причины выбрасывания исключения.

---

### ПодавленныеИсключения

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ПодавленныеИсключения: ЧитаемыйМассив<Исключение>
```

Исключения, которые были подавлены в процессе автоматического закрытия объектов типа [Закрываемое](../../wiki/stdlib/closeable-ru-67cd73fca69d.md).

---

### ПоследовательностьВызовов

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ПоследовательностьВызовов: Строка
```

Последовательность вызовов до места выбрасывания исключения.

---

### Причина

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Причина: Исключение?
```

Исключение, послужившее причиной выбрасывания текущего (если определено).

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

Возвращает тип исключения и описание, если не пустое.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

### Информация

`Доступность: КлиентИСервер`

```
Информация(): Строка
```

Возвращает информацию об исключении, содержащую описание, стек, информацию о причине и подавленных исключениях.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/stdlib/exception-ru-ed2632721976.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
