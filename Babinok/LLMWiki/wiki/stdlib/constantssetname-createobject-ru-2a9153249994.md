# {ИмяНабораКонстант}.СоздатьОбъект

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [constantssetname-createobject-ru-2a9153249994-633885632ba5c014](../../raw/text-10.0/constantssetname-createobject-ru-2a9153249994-633885632ba5c014.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ConstantsSetName.

Имена для поиска: `{ИмяНабораКонстант}.СоздатьОбъект`, `ConstantsSetName.CreateObject`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяНабораКонстант}.СоздатьОбъект`, `DeveloperName::ProjectName::SubsystemName::ConstantsSetName.CreateObject`.

## Обзор

Команда открытия формы новой записи набора констант.

## Документированный контракт и примеры

`Версия 9.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяНабораКонстант}.СоздатьОбъект` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы новой записи набора констант. Доступна только для периодических наборов.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяНабораКонстант}.АвтоматическаяФормаЗаписи
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](constantssetname-createobject-ru-2a9153249994.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../interface/usualcommand-ru-43da648bf5af.md), [Представление](../interface/usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../interface/usualcommand-ru-43da648bf5af.md), [Представление](../interface/usualcommand-ru-43da648bf5af.md)

## See Also

- [Навигатор раздела](../data/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [НаборКонстант — Элемент проекта](../project/constantsset-bae2805eef0b.md)
- [Хранимые данные и порождаемые типы](../data/entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](../data/object-form-and-crud.md)

Оригинал: [{ИмяНабораКонстант}.СоздатьОбъект](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ConstantsSetName.CreateObject_ru/).
