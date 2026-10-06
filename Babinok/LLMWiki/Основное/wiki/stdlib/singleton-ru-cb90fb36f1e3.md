# Одиночка

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [singleton-ru-cb90fb36f1e3-0cd43884f6da8582](../../raw/text-10.0/singleton-ru-cb90fb36f1e3-0cd43884f6da8582.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std.

Имена для поиска: `Одиночка`, `Singleton`, `Стд::Одиночка`, `Std::Singleton`.

## Обзор

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::Одиночка` `Доступность: КлиентИСервер`

Базовый тип всех одиночек.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

*Дочерние типы:* [HttpСервис](../integration/httpservice-ru-a5cc07d8bdea.md), [HttpСервисы](../integration/httpservices-ru-c3c21a436158.md), [Null](../data/null-ru-0059ad0ae7ba.md), [Авто](auto-ru-1b14ed166f8e.md), [Аутентификация](../security/authentication-ru-ff93cbd2ec8b.md), [БезопасноеХранилище](../interface/securestorage-ru-43304fadc791.md), [Безопасность](../security/security-ru-85d01bb8f863.md), [Блокировки](locks-ru-61cba2ed0544.md), [БуферОбмена](../interface/clipboard-ru-fb53761811e5.md), [ВыгрузкаФайлов](../interface/filesdownload-ru-97065aa8f041.md), [Геозоны](geofences-ru-83cd84b8485a.md), [Геолокация](geolocation-ru-2da56bf2b8c7.md), [Диалог](../interface/dialog-ru-c77b85fd9948.md), [Документ](../data/document-ru-b49d262f4dba.md), [Документы](../data/documents-ru-b82e2bc4bdfd.md), [ДоставляемыеУведомления](deliverablenotifications-ru-0db46eb15403.md), [ЖурналСобытий](eventlog-ru-390478c9ceb3.md), [ЗапланированныеЗадания](scheduledjobs-ru-1081e58e1cbc.md), [ИзбранноеПользователя](../interface/userfavorites-ru-e71189e469ca.md), [ИмяВыдаваемогоКлючаДоступа](../security/grantableaccesskeyname-ru-ef1ca4a7c1cf.md), [ИмяВычисляемогоКлючаДоступа](../security/computableaccesskeyname-ru-ab6483a7029c.md), [ИмяГлобальногоКлиентскогоСобытия](globalclienteventname-ru-99eaced091fa.md), [ИмяДокумента.ОткрытьСписок](../data/documentname-openlist-ru-eeda0f798e2f.md), [ИмяДокумента.СоздатьОбъект](../data/documentname-createobject-ru-edf1ad9b1831.md), [ИмяДокумента](../data/documentname-ru-a385526b4a75.md), [ИмяЖурналаДанных.ОткрытьСписок](datajournalname-openlist-ru-cb746a30d312.md), [ИмяЖурналаДанных](datajournalname-ru-529de137c48e.md), [ИмяИнтегрируемогоПриложения.ОткрытьСписок](integrableapplicationname-openlist-ru-cf5b5e36e7e8.md), [ИмяИнтегрируемогоПриложения.СоздатьОбъект](integrableapplicationname-createobject-ru-29d00b9c7a18.md), [ИмяИнтегрируемогоПриложения](integrableapplicationname-ru-dded7fda26a0.md), [ИмяКомандыНавигации](navigationcommandname-ru-e011f34476ce.md), [ИмяНабораКонстант.ОткрытьСписок](constantssetname-openlist-ru-9af058cb6e2e.md), [ИмяНабораКонстант.СоздатьОбъект](constantssetname-createobject-ru-2a9153249994.md), [ИмяНабораКонстант](constantssetname-ru-10721a2e334f.md), [ИмяНеПериодическогоНабораКонстант.ОткрытьОбъект](nonperiodicconstantssetname-openobject-ru-e3880953b129.md), [ИмяОбработки.Открыть](processingname-open-ru-d9588a5154bc.md), [ИмяОбработки](processingname-ru-9603ab69754c.md), [ИмяОбычнойКоманды](usualcommandname-ru-e1f0b94f3a77.md), [ИмяОтчета.Открыть](reportname-open-ru-7450dfd3a8ce.md), [ИмяПанелиОтчетов.Открыть](reportpanelname-open-ru-10d8d67aecf8.md), [ИмяПараметровРаботыКлиента](clientworkparametersname-ru-879b332058a3.md), [ИмяПереключаемойКоманды](switchablecommandname-ru-06c2e97ca102.md), [ИмяПланаОбмена.ОткрытьСписок](../integration/exchangeplanname-openlist-ru-5169161f614c.md), [ИмяПланаОбмена.СоздатьОбъект](../integration/exchangeplanname-createobject-ru-ecae22871288.md), [ИмяПланаОбмена](../integration/exchangeplanname-ru-5de5900381b1.md), [ИмяПодчиненногоРегистраСведений.ОткрытьСписок](../data/subordinatedinformationregistername-openlist-ru-a20b90ba7114.md), [ИмяПодчиненногоРегистраСведений](../data/subordinatedinformationregistername-ru-fcbbd736eae6.md), [ИмяПраваНаДействие](privilegeonactionname-ru-3650a0a22835.md), [ИмяПроцессаИнтеграции](../integration/integrationprocessname-ru-3968f78ee4f9.md), [ИмяРегистраНакопления.ОткрытьСписок](../data/accumulationregistername-openlist-ru-89b6018d8b7f.md), [ИмяРегистраНакопления](../data/accumulationregistername-ru-ca3f7a553094.md), [ИмяРегистраСведений.ОткрытьСписок](../data/informationregistername-openlist-ru-d5af0d432ae6.md), [ИмяРегистраСведений.СоздатьОбъект](../data/informationregistername-createobject-ru-3bd63e8333f5.md), [ИмяРегистраСведений](../data/informationregistername-ru-a758d6e52059.md), [ИмяСправочника.ОткрытьСписок](../data/catalogname-openlist-ru-d8eee47a1d8c.md), [ИмяСправочника.СоздатьОбъект](../data/catalogname-createobject-ru-0547549d53a0.md), [ИмяСправочника](../data/catalogname-ru-691a065c1965.md), [ИмяФрагментаКомандногоИнтерфейса](../interface/commandinterfacefragmentname-ru-b5957ec87d14.md), [ИмяХранилищаНастроек.ОткрытьСписок](../data/settingsstoragename-openlist-ru-c3bec24005a0.md), [ИмяХранилищаНастроек.СоздатьОбъект](../data/settingsstoragename-createobject-ru-5f6b2fe2d3f3.md), [ИмяХранилищаНастроек](../data/settingsstoragename-ru-f7a28628e636.md), [ИнтегрируемоеПриложение](integrableapplication-ru-5607393f6b9e.md), [ИнтегрируемыеПриложения](integrableapplications-ru-0825bc1c040a.md), [ИсторияРаботыПользователя](../interface/userworkhistory-ru-ad103b9e3c6d.md), [КешРезультатовМетодов](methodsresultscache-ru-eb66d8b3e71f.md), [КлиентSmtp](../integration/smtpclient-ru-c3362704371b.md), [КлиентскоеУстройство](../interface/clientdevice-ru-ebb2cc5db0ee.md), [КлючДоступа](../security/accesskey-ru-10faf3f17fff.md), [КлючДоступаДляАутентифицированных](../security/accesskeyforauthenticated-ru-10a3076a3d4e.md), [КлючДоступаДляВсех](../security/accesskeyforeveryone-ru-4a12798615d1.md), [КлючДоступаПользователя](../security/useraccesskey-ru-3d9e14563e1e.md), [КлючиДоступа](../security/accesskeys-ru-366038857e8d.md), [Кодировки](encodings-ru-482328836e27.md), [КонтрольДоступа](accesscontrol-ru-4a29c8df78bf.md), [КонтрольнаяСумма](checksum-ru-a59ddb6d3dec.md), [Криптография](cryptography-ru-05a6d9cc02a9.md), [Мультимедиа](../interface/multimedia-ru-811323b6eb52.md), [НаборКонстант](constantsset-ru-8ee9270478c2.md), [НавигационнаяКомандаИнформационныеСистемы](../interface/navigationcommandinformationsystems-ru-abefad73a4bb.md), [НавигационнаяКомандаПроцессыИнтеграции](../interface/navigationcommandintegrationprocesses-ru-bbe38601de37.md), [НеудаленныеОбъекты](undeletedobjects-ru-35dc33d952c0.md), [Обработка](processing-ru-84121167c052.md), [ОбъектноеХранилище](../data/objectstorage-ru-2ba8627c997d.md), [ОперацииСамообслуживания](selfserviceoperations-ru-0b345917307a.md), [ОтправкаДоставляемыхУведомлений](deliverablenotificationssender-ru-785afe0b1543.md), [Отчеты](reports-ru-eebb8215f5b8.md), [ПланОбмена](../integration/exchangeplan-ru-a145e72bb1fa.md), [ПланыОбмена](../integration/exchangeplans-ru-655d42bfe00f.md), [ПобитовыеОперации](bitwiseoperations-ru-23e055c3e446.md), [ПолнотекстовыйПоиск](fulltextsearch-ru-c78a302cd212.md), [Пользователи](users-ru-f417ba72157b.md), [ПользователиСервиса](serviceusers-ru-558e621dc6f7.md), [ПриглашенияЕдиногоМобильногоКлиента](unifiedmobileclientinvitations-ru-46904aaa1a8f.md), [ПроверкаXml](../integration/xmlvalidator-ru-c2234a82a3f3.md), [ПроцессыИнтеграции](../integration/integrationprocesses-ru-4be1b15b2eed.md), [РегистрНакопления](../data/accumulationregister-ru-7f448489c031.md), [РегистрСведений](../data/informationregister-ru-d15b0965bc15.md), [РегистрацияВебЧата](../data/webchatregistration-ru-eaca654bb74c.md), [РегистрыНакопления](../data/accumulationregisters-ru-906ed7644b39.md), [РегистрыСведений](../data/informationregisters-ru-07c5a36c9826.md), [СериализацияJson](../integration/jsonserialization-ru-d810a802893e.md), [Символы](chars-ru-293d51e47e12.md), [СистемаВзаимодействия](../integration/collaborationsystem-ru-51561bd68a2c.md), [СпискиПользователей](userlists-ru-ef3df4f80ede.md), [Справочник](../data/catalog-ru-2804b6898555.md), [Справочники](../data/catalogs-ru-7e6f432a1874.md), [СредаИсполнения](executionenvironment-ru-24233cd6ac41.md), [СтандартноеХранилищеНастроек.ОткрытьСписок](../data/standardsettingsstorage-openlist-ru-8307e16e9c77.md), [СтандартноеХранилищеНастроек.СоздатьОбъект](../data/standardsettingsstorage-createobject-ru-76a8bb7aa0fd.md), [СтандартноеХранилищеНастроек](../data/standardsettingsstorage-ru-45df1deaf228.md), [СтандартныеСемействаШрифтов](../interface/standardfontfamilies-ru-0b136be498aa.md), [СтатистикаИспользованияПриложения](../interface/applicationusagestatistics-ru-83339db78941.md), [СтилевыеШрифты](../interface/stylefonts-ru-ea7afd51c776.md), [Строки](strings-ru-2fc86f02f9b2.md), [Транзакции](../data/transactions-ru-8a250515b869.md), [УправлениеПриложениямиВзаимодействия](../integration/collaborationapplicationsmanagement-ru-437d8f88f8c5.md), [УтилитыБазыДанных](../data/databaseutils-ru-9887e02112be.md), [Файлы](files-ru-b86b3889e2c8.md), [ФоновыеЗадания](backgroundjobs-ru-ce0a20cb1908.md), [ХранилищаНастроек](../data/settingsstorages-ru-9ed06f04ee66.md), [ХранилищеНастроек](../data/settingsstorage-ru-0bb23ad2852d.md), [Цвета](colors-ru-a841affb57c9.md)

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

Оригинал: [Одиночка](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Singleton_ru/).
