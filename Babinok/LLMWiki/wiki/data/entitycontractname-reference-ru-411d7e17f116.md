# {ИмяКонтрактаСущности}.Ссылка

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [entitycontractname-reference-ru-411d7e17f116-c20aee6ae8b3717b](../../raw/text-10.0/entitycontractname-reference-ru-411d7e17f116-c20aee6ae8b3717b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: EntityContractName.

Имена для поиска: `{ИмяКонтрактаСущности}.Ссылка`, `EntityContractName.Reference`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяКонтрактаСущности}.Ссылка`, `DeveloperName::ProjectName::SubsystemName::EntityContractName.Reference`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md), [Сущность.Ключ](entity-key-ru-7032eabc056b.md), [Сущность.Ссылка](entity-reference-ru-d0485ecb981e.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяКонтрактаСущности}.Ссылка` `Доступность: КлиентИСервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md), [Сущность.Ключ](entity-key-ru-7032eabc056b.md), [Сущность.Ссылка](entity-reference-ru-d0485ecb981e.md)

---

## Свойства

### Ид

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Ид: Ууид
```

Переопределение: [Ид](entitycontractname-reference-ru-411d7e17f116.md)

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../stdlib/object-ru-9e351f286699.md)

---

### ЗагрузитьОбъект

`Доступность: Сервер`

```
ЗагрузитьОбъект(Заблокировать: Булево = Ложь): {ИмяКонтрактаСущности}.Объект?
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](entitycontractname-reference-ru-411d7e17f116.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

### Представляемое

[Представление](../stdlib/presentable-ru-fc7455a0880f.md)

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [КонтрактСущности — Элемент проекта](entitycontract-ef962eb24775.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [{ИмяКонтрактаСущности}.Ссылка](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/EntityContractName.Reference_ru/).
