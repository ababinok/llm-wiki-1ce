# {ИмяСправочника}.СоздатьОбъект

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [catalogname-createobject-ru-0547549d53a0-978cbbf2d479b013](../../raw/text-10.0/catalogname-createobject-ru-0547549d53a0-978cbbf2d479b013.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: CatalogName.

Имена для поиска: `{ИмяСправочника}.СоздатьОбъект`, `CatalogName.CreateObject`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяСправочника}.СоздатьОбъект`, `DeveloperName::ProjectName::SubsystemName::CatalogName.CreateObject`.

## Обзор

Команда открытия формы нового объекта справочника.

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяСправочника}.СоздатьОбъект` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы нового объекта справочника.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](../stdlib/object-ru-9e351f286699.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](../stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяСправочника}.АвтоматическаяФормаОбъекта
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](catalogname-createobject-ru-0547549d53a0.md)

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
- [Элемент проекта вида «Справочник» — Руководство](catalog-project-element-b6ca52d114d4.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [Справочник — Элемент проекта](catalog-e0da7d4e8e72.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [{ИмяСправочника}.СоздатьОбъект](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/CatalogName.CreateObject_ru/).
