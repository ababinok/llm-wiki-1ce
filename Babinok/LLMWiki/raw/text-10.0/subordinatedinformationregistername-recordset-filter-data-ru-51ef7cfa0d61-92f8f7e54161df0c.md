# {ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SubordinatedInformationRegisterName.RecordSet.Filter.Data_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SubordinatedInformationRegisterName.RecordSet.Filter.Data_ru/index.html
> SHA256: 1f4aad9aef266254f4c71a56293704a07dc1977e342c39fa27e23dcdc7f537b9
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр.Данные` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [РегистрСведений.НаборЗаписей.Фильтр](../../wiki/data/informationregister-recordset-filter-ru-2dce74307180.md), [Сущность.НаборЗаписей.Фильтр](../../wiki/data/entity-recordset-filter-ru-54579d6f4b8c.md)

---

## Свойства

### КлючОсновногоФильтра

`Доступность: Сервер` `ТолькоЧтение`

```
КлючОсновногоФильтра: {ИмяПодчиненногоРегистраСведений}.КлючОсновногоФильтра
```

Содержит измерения, которые включены в основной фильтр, и период для периодического регистра сведений, если период включен в основной фильтр.

Переопределение: [КлючОсновногоФильтра](../../wiki/data/subordinatedinformationregistername-recordset-filter-data-ru-51ef7cfa0d61.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### Сущность.НаборЗаписей.Фильтр

[Инициализирован](../../wiki/data/entity-recordset-filter-ru-54579d6f4b8c.md)
