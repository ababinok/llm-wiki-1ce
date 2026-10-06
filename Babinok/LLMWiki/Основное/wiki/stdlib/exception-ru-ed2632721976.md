# Исключение

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [exception-ru-ed2632721976-0d88cf546c84e3cc](../../raw/text_10_0/exception-ru-ed2632721976-0d88cf546c84e3cc.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std.

Имена для поиска: `Исключение`, `Exception`, `Стд::Исключение`, `Std::Exception`.

## Обзор

Базовый тип любого исключения.

## Документированный контракт и примеры

`Стд::Исключение` `Доступность: КлиентИСервер`

Базовый тип любого исключения. Объекты данного типа можно выбросить с помощью инструкции `выбросить` и перехватывать в секции `поймать` блока `попытка`.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

*Дочерние типы:* [ИсключениеFtp](ftpexception-ru-132dadd916c0.md), [ИсключениеHttp](../integration/httpexception-ru-2140341cd0ec.md), [ИсключениеPaas](paasexception-ru-58e007c03606.md), [ИсключениеPdf](pdfexception-ru-fca07efa7071.md), [ИсключениеSftp](../integration/sftpexception-ru-b1502c5e1bd8.md), [ИсключениеSql](../data/sqlexception-ru-c108d8de1746.md), [ИсключениеSsh](../integration/sshexception-ru-96483eea9a34.md), [ИсключениеАдминистрированияКластера](administrationclusterexception-ru-a77ecbabe797.md), [ИсключениеАрифметики](arithmeticexception-ru-fd5e53d78c0b.md), [ИсключениеБезопасногоХранилища](../interface/securestorageexception-ru-2e9de5b75101.md), [ИсключениеБуфераОбмена](../interface/clipboardexception-ru-60397212f434.md), [ИсключениеВалидации](validationexception-ru-e71e5b661e18.md), [ИсключениеВводаВывода](inputoutputexception-ru-ceba5f672999.md), [ИсключениеВерификацииПользователя](../interface/userverificationexception-ru-b18aa1737905.md), [ИсключениеВзаимоблокировка](deadlockexception-ru-c6366ebdf84e.md), [ИсключениеВнутренняяОшибкаВыполненияЗадания](jobexecutioninternalerrorexception-ru-881eb62ccbab.md), [ИсключениеВызоваSoapСервиса](../integration/soapservicecallexception-ru-928205adb79d.md), [ИсключениеВызоваСобытия](../interface/eventcallexception-ru-b0fcb44ab497.md), [ИсключениеВыполненияJs](../interface/jsexecutionexception-ru-436350b62184.md), [ИсключениеВыполнения](executionexception-ru-98406726cb92.md), [ИсключениеГенерацииQrКода](qrcodegenerationexception-ru-cb199f61d719.md), [ИсключениеГеозон](geofenceexception-ru-19cbe9afb179.md), [ИсключениеДвоичногоОбъекта](../data/binaryobjectexception-ru-ccf2a7416223.md), [ИсключениеДинамическогоВыполнения](dynamicexecutionexception-ru-30d60771d2af.md), [ИсключениеДокументаHtml](../data/htmldocumentexception-ru-6ea628ca38f8.md), [ИсключениеДоставляемыхУведомлений](deliverablenotificationexception-ru-cbf2a39d4997.md), [ИсключениеДоступЗапрещен](accessdeniedexception-ru-f679f509f3e4.md), [ИсключениеДоступаКСекрету](../security/secretaccessexception-ru-b71fa04e142e.md), [ИсключениеДоступаКСредеИсполнения](../security/executionenvironmentpermissionexception-ru-7a816a1b673d.md), [ИсключениеДоступаКФайлу](../security/filepermissionexception-ru-c4b7f0af5ac2.md), [ИсключениеЗагрузкаФайлаОтменена](../interface/fileuploadcanceledexception-ru-547f1577d835.md), [ИсключениеЗагрузкиДвоичногоОбъекта](../data/binaryobjectuploadexception-ru-f7b277993953.md), [ИсключениеЗаданиеОтменено](jobcanceledexception-ru-85ca9a9057fc.md), [ИсключениеЗаписиJson](../integration/jsonwriterexception-ru-9073a0c1344f.md), [ИсключениеЗаписиXml](../integration/xmlwriterexception-ru-a4b2974dbea2.md), [ИсключениеЗаписьНеМожетБытьИзменена](recordcannotbeupdatedexception-ru-7451959e658a.md), [ИсключениеЗаписьНеМожетБытьУдалена](recordcannotbedeletedexception-ru-55e7aeddc198.md), [ИсключениеЗаписьНеУникальна](recordnotuniqueexception-ru-ac3c448c69da.md), [ИсключениеЗапроса](../queries/queryexception-ru-aa570351115a.md), [ИсключениеЗначениеСвойстваНеУникально](propertyvaluenotuniqueexception-ru-ad124b3a4ec2.md), [ИсключениеИндексВнеГраниц](indexoutofboundsexception-ru-2b34a623369c.md), [ИсключениеИнтеграционнойШины](../integration/integrationbusexception-ru-0bbe235ac154.md), [ИсключениеИсточникКопированияСущностиНеСуществует](../data/entitycopysourcenotexistsexception-ru-ccae6b569bee.md), [ИсключениеКомпиляции](compileexception-ru-579bf6b6839e.md), [ИсключениеКомпонентНеГотов](../interface/componentnotreadyexception-ru-8f818b439334.md), [ИсключениеКриптографии](cryptoexception-ru-9269fbee8009.md), [ИсключениеМультимедиа](../interface/multimediaexception-ru-9913f65f68cd.md), [ИсключениеНедопустимоеСостояние](illegalstateexception-ru-4c1cc853b874.md), [ИсключениеНедопустимоеСостояниеТранзакции](../data/illegaltransactionstateexception-ru-eb3ecacffa4d.md), [ИсключениеНедопустимыйАргумент](illegalargumentexception-ru-fc532bf88932.md), [ИсключениеНедопустимыйФормат](illegalformatexception-ru-8ff587175d1a.md), [ИсключениеНекорректноеРегулярноеВыражение](illegalregularexpressionexception-ru-b4ae057eb659.md), [ИсключениеНеподдерживаемаяОперация](unsupportedoperationexception-ru-6fc50eac7766.md), [ИсключениеНесоответствияВладельцевИерархии](hierarchyownersmismatchexception-ru-0887bade9def.md), [ИсключениеНумерации](numberingexception-ru-5d3b90192a0f.md), [ИсключениеОбработчикФоновогоЗаданияНеНайден](backgroundjobhandlernotfoundexception-ru-1bdcdb876ba3.md), [ИсключениеОдновременноеИзменениеСущности](../data/concurrententitymodificationexception-ru-0b6f275abc3d.md), [ИсключениеОтражения](reflectionexception-ru-eaf98f596473.md), [ИсключениеПапкаИзбранногоПользователяНеСуществует](../interface/userfavoritesfoldernotexistsexception-ru-617124f37903.md), [ИсключениеПапкаИзбранногоПользователяНеУникальна](../interface/userfavoritesfoldernotuniqueexception-ru-3b54669191b2.md), [ИсключениеПараметрыРаботыКлиентаНеИнициализированы](../interface/clientworkparametersnotinitializedexception-ru-852da47af9f8.md), [ИсключениеПоискаXPath](../integration/xpathsearchexception-ru-680675674c5a.md), [ИсключениеПоискаСущности](../data/entitysearchexception-ru-ae3d905c5b5f.md), [ИсключениеПолнотекстовогоПоиска](fulltextsearchexception-ru-b26a54521aae.md), [ИсключениеПостроенияXmlDom](../integration/xmldombuildexception-ru-18c59d9ac500.md), [ИсключениеПостроенияГеографическогоМаршрута](geographicroutebuildingexception-ru-62c291947120.md), [ИсключениеПочты](emailexception-ru-daee01e8e961.md), [ИсключениеПреобразованияXml](../integration/xmltransformationexception-ru-6f9c954f3882.md), [ИсключениеПриглашенияЕдиногоМобильногоКлиента](unifiedmobileclientinvitationexception-ru-57368b91aad6.md), [ИсключениеПроверкиXml](../integration/xmlvalidationexception-ru-52055d7c2301.md), [ИсключениеПроверкиТипа](typecheckexception-ru-d4c24f2f9eee.md), [ИсключениеРазрешениеОтсутствует](../security/nopermissionexception-ru-1f930860881b.md), [ИсключениеРесурсНеНайден](resourcenotfoundexception-ru-9455193031c3.md), [ИсключениеСервера](../interface/serverexception-ru-c5830d7da0f3.md), [ИсключениеСистемыВзаимодействия](../integration/collaborationsystemexception-ru-f8d82f9023f2.md), [ИсключениеСравнения](compareexception-ru-66603110ce3a.md), [ИсключениеСсылкаНеУникальна](referencenotuniqueexception-ru-e8aba27ec85c.md), [ИсключениеСущностьНеЗаписана](../data/entitynotwrittenexception-ru-bf648734c903.md), [ИсключениеТабличногоДокумента](spreadsheetexception-ru-5cca8ccd5cbf.md), [ИсключениеТаймаутаБлокировки](locktimeoutexception-ru-944ade356519.md), [ИсключениеТаймаутаЗадания](jobtimeoutexception-ru-84b1e550fa23.md), [ИсключениеУправленияПользователями](usermanagementexception-ru-9741246a36bd.md), [ИсключениеФайловойСистемы](filesystemexception-ru-fd95df425388.md), [ИсключениеХешированияДанных](datahashingexception-ru-11502d9b8867.md), [ИсключениеЦиклВИерархии](cycleinhierarchyexception-ru-1a6ef43231a5.md), [ИсключениеЧтенияJson](../integration/jsonreaderexception-ru-62be4dbb30ff.md), [ИсключениеЧтенияXml](../integration/xmlreaderexception-ru-0d8061eee533.md), [ИсключениеЧтенияДанных](datareadexception-ru-8323ffdb9fa5.md), [ИсключениеЭкспортаОтчета](reportexportexception-ru-a8fa5d8929ac.md), [ИсключениеЭлементИзбранногоПользователяНеСуществует](../interface/userfavoritesitemnotexistsexception-ru-b3339fa55f53.md), [ИсключениеЭлементИзбранногоПользователяНеУникален](../interface/userfavoritesitemnotuniqueexception-ru-4d9fae2391ac.md)

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

Исключения, которые были подавлены в процессе автоматического закрытия объектов типа [Закрываемое](closeable-ru-67cd73fca69d.md).

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

**Переопределение** [Объект::ВСтроку](object-ru-9e351f286699.md)

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

[ВСтроку](object-ru-9e351f286699.md) [(Переопределение)](exception-ru-ed2632721976.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд — Пространство имён XBSL: Std](std-c15458c2f5f0.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [Исключение](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Exception_ru/).
