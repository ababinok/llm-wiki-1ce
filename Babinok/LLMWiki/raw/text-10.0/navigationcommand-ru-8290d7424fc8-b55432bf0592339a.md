# НавигационнаяКоманда

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Commands/NavigationCommand_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Commands/NavigationCommand_ru/index.html
> SHA256: b692cf06452a53511c682bf381dc7da00c3172290104ab0255e01f55fbea897a
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Команды::НавигационнаяКоманда` `Доступность: Клиент`

Навигационная команда. Результатом выполнения является открытая форма.

**Сравнение**

Ссылочное

Структурное сравнение.

## Иерархия типа

*Базовые типы:* [Команда](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../../wiki/interface/usualcommand-ru-43da648bf5af.md)

*Дочерние типы:* [ИмяДокумента.ОткрытьСписок](../../wiki/data/documentname-openlist-ru-eeda0f798e2f.md), [ИмяДокумента.СоздатьОбъект](../../wiki/data/documentname-createobject-ru-edf1ad9b1831.md), [ИмяЖурналаДанных.ОткрытьСписок](../../wiki/stdlib/datajournalname-openlist-ru-cb746a30d312.md), [ИмяИнтегрируемогоПриложения.ОткрытьСписок](../../wiki/stdlib/integrableapplicationname-openlist-ru-cf5b5e36e7e8.md), [ИмяИнтегрируемогоПриложения.СоздатьОбъект](../../wiki/stdlib/integrableapplicationname-createobject-ru-29d00b9c7a18.md), [ИмяКомандыНавигации](../../wiki/stdlib/navigationcommandname-ru-e011f34476ce.md), [ИмяНабораКонстант.ОткрытьСписок](../../wiki/stdlib/constantssetname-openlist-ru-9af058cb6e2e.md), [ИмяНабораКонстант.СоздатьОбъект](../../wiki/stdlib/constantssetname-createobject-ru-2a9153249994.md), [ИмяНеПериодическогоНабораКонстант.ОткрытьОбъект](../../wiki/stdlib/nonperiodicconstantssetname-openobject-ru-e3880953b129.md), [ИмяОбработки.Открыть](../../wiki/stdlib/processingname-open-ru-d9588a5154bc.md), [ИмяОтчета.Открыть](../../wiki/stdlib/reportname-open-ru-7450dfd3a8ce.md), [ИмяПанелиОтчетов.Открыть](../../wiki/stdlib/reportpanelname-open-ru-10d8d67aecf8.md), [ИмяПланаОбмена.ОткрытьСписок](../../wiki/integration/exchangeplanname-openlist-ru-5169161f614c.md), [ИмяПланаОбмена.СоздатьОбъект](../../wiki/integration/exchangeplanname-createobject-ru-ecae22871288.md), [ИмяПодчиненногоРегистраСведений.ОткрытьСписок](../../wiki/data/subordinatedinformationregistername-openlist-ru-a20b90ba7114.md), [ИмяРегистраНакопления.ОткрытьСписок](../../wiki/data/accumulationregistername-openlist-ru-89b6018d8b7f.md), [ИмяРегистраСведений.ОткрытьСписок](../../wiki/data/informationregistername-openlist-ru-d5af0d432ae6.md), [ИмяРегистраСведений.СоздатьОбъект](../../wiki/data/informationregistername-createobject-ru-3bd63e8333f5.md), [ИмяСправочника.ОткрытьСписок](../../wiki/data/catalogname-openlist-ru-d8eee47a1d8c.md), [ИмяСправочника.СоздатьОбъект](../../wiki/data/catalogname-createobject-ru-0547549d53a0.md), [ИмяХранилищаНастроек.ОткрытьСписок](../../wiki/data/settingsstoragename-openlist-ru-c3bec24005a0.md), [ИмяХранилищаНастроек.СоздатьОбъект](../../wiki/data/settingsstoragename-createobject-ru-5f6b2fe2d3f3.md), [НавигационнаяКомандаИнформационныеСистемы](../../wiki/interface/navigationcommandinformationsystems-ru-abefad73a4bb.md), [НавигационнаяКомандаПроцессыИнтеграции](../../wiki/interface/navigationcommandintegrationprocesses-ru-bbe38601de37.md), [СтандартноеХранилищеНастроек.ОткрытьСписок](../../wiki/data/standardsettingsstorage-openlist-ru-8307e16e9c77.md), [СтандартноеХранилищеНастроек.СоздатьОбъект](../../wiki/data/standardsettingsstorage-createobject-ru-76a8bb7aa0fd.md)

---

## Конструкторы

### НавигационнаяКоманда

`Версия 9.0 и выше`

`Доступность: Клиент`

```
НавигационнаяКоманда(
  Представление: Строка,
  Изображение: Url|ДвоичныйОбъект.Ссылка|? = Неопределено,
  ТипФормы: Тип<Форма<неизвестно>>, Важность: ВажностьКоманды = ВажностьКоманды.Обычная, Доступность: Булево = Истина, Видимость: Булево = Истина, ОпасностьДействия: ОпасностьДействия = ОпасностьДействия.Отсутствует)
```

Создает навигационную команду с заданными полями.

---

### НавигационнаяКоманда

`Версия 8.0 и ниже`

`Доступность: Клиент`

```
НавигационнаяКоманда(
  Представление: Строка,
  Изображение: ДвоичныйОбъект.Ссылка? = Неопределено,
  ТипФормы: Тип<Форма<неизвестно>>, Важность: ВажностьКоманды = ВажностьКоманды.Обычная, Доступность: Булево = Истина, Видимость: Булево = Истина, ОпасностьДействия: ОпасностьДействия = ОпасностьДействия.Отсутствует)
```

Конструктор удален.

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): Форма<неизвестно>
```

Возвращает форму, которая была бы открыта в случае исполнения команды.

---

## Список унаследованных методов

### Команда

[Выполнить](../../wiki/interface/command-ru-ad3bc8ea1407.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Видимость](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Доступность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../../wiki/interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../../wiki/interface/usualcommand-ru-43da648bf5af.md), [Представление](../../wiki/interface/usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Видимость](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Доступность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../../wiki/interface/command-ru-ad3bc8ea1407.md)
