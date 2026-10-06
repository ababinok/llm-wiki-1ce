# {ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [subordinatedinformationregistername-recordset-filter-data-ru-51ef7cfa0d61-92f8f7e54161df0c](../../raw/text-10.0/subordinatedinformationregistername-recordset-filter-data-ru-51ef7cfa0d61-92f8f7e54161df0c.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: SubordinatedInformationRegisterName.

Имена для поиска: `{ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные`, `SubordinatedInformationRegisterName.RecordSet.Filter.Data`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные`, `DeveloperName::ProjectName::SubsystemName::SubordinatedInformationRegisterName.RecordSet.Filter.Data`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [РегистрСведений.НаборЗаписей.Фильтр](informationregister-recordset-filter-ru-2dce74307180.md), [Сущность.НаборЗаписей.Фильтр](entity-recordset-filter-ru-54579d6f4b8c.md)

## Документированный контракт и примеры

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [РегистрСведений.НаборЗаписей.Фильтр](informationregister-recordset-filter-ru-2dce74307180.md), [Сущность.НаборЗаписей.Фильтр](entity-recordset-filter-ru-54579d6f4b8c.md)

---

## Свойства

### КлючОсновногоФильтра

`Доступность: Сервер` `ТолькоЧтение`

```
КлючОсновногоФильтра: {ИмяПодчиненногоРегистраСведений}.КлючОсновногоФильтра
```

Содержит измерения, которые включены в основной фильтр, и период для периодического регистра сведений, если период включен в основной фильтр.

Переопределение: [КлючОсновногоФильтра](subordinatedinformationregistername-recordset-filter-data-ru-51ef7cfa0d61.md)

---

### Регистратор

`Доступность: Сервер` `ТолькоЧтение`

```
Регистратор: Сущность.НаборЗаписей.Фильтр.Элемент<{ИмяДокумента}.Ссылка?>
```

Содержит ссылку на документ-регистратор, по которому выполняется отбор записей.

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

### Сущность.НаборЗаписей.Фильтр

[Инициализирован](entity-recordset-filter-ru-54579d6f4b8c.md)

## See Also

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SubordinatedInformationRegisterName.RecordSet.Filter.Data_ru/).
