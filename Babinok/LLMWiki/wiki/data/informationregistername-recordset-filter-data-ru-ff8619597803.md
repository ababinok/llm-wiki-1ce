# {ИмяРегистраСведений}.НаборЗаписей.Фильтр.Данные

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [informationregistername-recordset-filter-data-ru-ff8619597803-c0df81a3167c0300](../../raw/text-10.0/informationregistername-recordset-filter-data-ru-ff8619597803-c0df81a3167c0300.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: InformationRegisterName.

Имена для поиска: `{ИмяРегистраСведений}.НаборЗаписей.Фильтр.Данные`, `InformationRegisterName.RecordSet.Filter.Data`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяРегистраСведений}.НаборЗаписей.Фильтр.Данные`, `DeveloperName::ProjectName::SubsystemName::InformationRegisterName.RecordSet.Filter.Data`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [РегистрСведений.НаборЗаписей.Фильтр](informationregister-recordset-filter-ru-2dce74307180.md), [Сущность.НаборЗаписей.Фильтр](entity-recordset-filter-ru-54579d6f4b8c.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяРегистраСведений}.НаборЗаписей.Фильтр.Данные` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [РегистрСведений.НаборЗаписей.Фильтр](informationregister-recordset-filter-ru-2dce74307180.md), [Сущность.НаборЗаписей.Фильтр](entity-recordset-filter-ru-54579d6f4b8c.md)

---

## Свойства

### {ИмяИзмерения}

`Доступность: Сервер` `ТолькоЧтение`

```
ИмяИзмерения: Сущность.НаборЗаписей.Фильтр.Элемент<{ИмяСправочника}.Ссылка?>
```

---

### КлючОсновногоФильтра

`Доступность: Сервер` `ТолькоЧтение`

```
КлючОсновногоФильтра: {ИмяРегистраСведений}.КлючОсновногоФильтра
```

Переопределение: [КлючОсновногоФильтра](informationregistername-recordset-filter-data-ru-ff8619597803.md)

---

### Период

`Доступность: Сервер` `ТолькоЧтение`

```
Период: Сущность.НаборЗаписей.Фильтр.Элемент<Дата>
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

### Сущность.НаборЗаписей.Фильтр

[Инициализирован](entity-recordset-filter-ru-54579d6f4b8c.md)

## See Also

- [Навигатор раздела](overview.md)
- [Элемент проекта вида «РегистрСведений» — Руководство](information-register-project-element-8932693c91b1.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [РегистрСведений — Элемент проекта](informationregister-10bb0480b19f.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [{ИмяРегистраСведений}.НаборЗаписей.Фильтр.Данные](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/InformationRegisterName.RecordSet.Filter.Data_ru/).
