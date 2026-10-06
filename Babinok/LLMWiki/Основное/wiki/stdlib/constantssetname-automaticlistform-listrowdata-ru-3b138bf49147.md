# {ИмяНабораКонстант}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [constantssetname-automaticlistform-listrowdata-ru-3b138bf49147-8a9f123b5745c063](../../raw/text_10_0/constantssetname-automaticlistform-listrowdata-ru-3b138bf49147-8a9f123b5745c063.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ConstantsSetName.

Имена для поиска: `{ИмяНабораКонстант}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка`, `ConstantsSetName.AutomaticListForm.ListRowData`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяНабораКонстант}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка`, `DeveloperName::ProjectName::SubsystemName::ConstantsSetName.AutomaticListForm.ListRowData`.

## Обзор

*Базовые типы:* [ДанныеСтрокиДинамическогоСписка<Объект>](../interface/dynamiclistrowdata-ru-944b789a8d8c.md), [Объект](object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Версия 9.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяНабораКонстант}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка` `Доступность: Клиент`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ДанныеСтрокиДинамическогоСписка<Объект>](../interface/dynamiclistrowdata-ru-944b789a8d8c.md), [Объект](object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяНабораКонстант}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка

`Доступность: Клиент`

```
ИмяНабораКонстант.АвтоматическаяФормаСписка.ДанныеСтрокиСписка(
  Period: Дата,
  ConstantName: Число)
```

---

## Свойства

### ConstantName

`Доступность: Клиент` `ТолькоЧтение`

```
ConstantName: Число
```

---

### Period

`Доступность: Клиент` `ТолькоЧтение`

```
Period: Дата
```

---

## Методы

### ВСтроку

`Доступность: Клиент`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md) [(Переопределение)](constantssetname-automaticlistform-listrowdata-ru-3b138bf49147.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../data/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [НаборКонстант — Элемент проекта](../project/constantsset-bae2805eef0b.md)
- [Хранимые данные и порождаемые типы](../data/entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](../data/object-form-and-crud.md)

Оригинал: [{ИмяНабораКонстант}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ConstantsSetName.AutomaticListForm.ListRowData_ru/).
