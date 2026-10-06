# {ИмяХранилищаНастроек}.ОткрытьСписок

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [settingsstoragename-openlist-ru-c3bec24005a0-d237786d3c62aabd](../../raw/text-10.0/settingsstoragename-openlist-ru-c3bec24005a0-d237786d3c62aabd.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: SettingsStorageName.

Имена для поиска: `{ИмяХранилищаНастроек}.ОткрытьСписок`, `SettingsStorageName.OpenList`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяХранилищаНастроек}.ОткрытьСписок`, `DeveloperName::ProjectName::SubsystemName::SettingsStorageName.OpenList`.

## Обзор

Команда открытия формы списка объектов хранилища настроек.

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяХранилищаНастроек}.ОткрытьСписок` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы списка объектов хранилища настроек.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](../stdlib/object-ru-9e351f286699.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](../stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяХранилищаНастроек}.АвтоматическаяФормаСписка
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](settingsstoragename-openlist-ru-c3bec24005a0.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

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

- [Навигатор раздела](overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [ХранилищеНастроек — Элемент проекта](settingsstorage-c57f34254260.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [{ИмяХранилищаНастроек}.ОткрытьСписок](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SettingsStorageName.OpenList_ru/).
