# {ИмяЖурналаДанных}.ОткрытьСписок

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [datajournalname-openlist-ru-cb746a30d312-32a8d318e7a7f63c](../../raw/text_10_0/datajournalname-openlist-ru-cb746a30d312-32a8d318e7a7f63c.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: DataJournalName.

Имена для поиска: `{ИмяЖурналаДанных}.ОткрытьСписок`, `DataJournalName.OpenList`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяЖурналаДанных}.ОткрытьСписок`, `DeveloperName::ProjectName::SubsystemName::DataJournalName.OpenList`.

## Обзор

Команда открытия формы списка журнала данных.

## Документированный контракт и примеры

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяЖурналаДанных}.ОткрытьСписок` `Тип-одиночка` `@ВПодсистеме` `Доступность: Клиент`

Команда открытия формы списка журнала данных.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяЖурналаДанных}.АвтоматическаяФормаСписка
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](datajournalname-openlist-ru-cb746a30d312.md)

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
- [Элемент проекта вида «ЖурналДанных» — Руководство](../project/data-journal-project-element-7531ea42bb4a.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [ЖурналДанных — Элемент проекта](../project/datajournal-3d0e7aa19753.md)
- [Хранимые данные и порождаемые типы](../data/entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](../data/object-form-and-crud.md)

Оригинал: [{ИмяЖурналаДанных}.ОткрытьСписок](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/DataJournalName.OpenList_ru/).
