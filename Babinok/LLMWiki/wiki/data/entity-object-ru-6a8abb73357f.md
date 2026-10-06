# Сущность.Объект

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [entity-object-ru-6a8abb73357f-ca7c8d74017a719e](../../raw/text-10.0/entity-object-ru-6a8abb73357f-ca7c8d74017a719e.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Entities.

Имена для поиска: `Сущность.Объект`, `Entity.Object`, `Стд::Сущности::Сущность.Объект`, `Std::Entities::Entity.Object`.

## Обзор

Базовый тип всех объектных типов сущностей.

## Документированный контракт и примеры

`Стд::Сущности::Сущность.Объект` `Доступность: КлиентИСервер`

Базовый тип всех объектных типов сущностей.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md)

*Дочерние типы:* [Документ.Объект](document-object-ru-25b2a8d67db3.md), [ИмяКонтрактаСущности.Объект](entitycontractname-object-ru-9fb448fd439a.md), [ИнтегрируемоеПриложение.Объект](../stdlib/integrableapplication-object-ru-cbb0fa9c9f27.md), [ПланОбмена.Объект](../integration/exchangeplan-object-ru-48ca2a14383b.md), [Справочник.Объект](catalog-object-ru-4a8f48525cd3.md), [СправочникИнформационныхСистем.Объект](../integration/informationsystemscatalog-object-ru-ad6adb24f082.md), [ХранилищеНастроек.Объект](settingsstorage-object-ru-0ed39bf10f11.md)

---

## Свойства

### Ссылка

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Ссылка: Сущность.Ключ
```

Ссылка на сущность.

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

### Представляемое

[Представление](../stdlib/presentable-ru-fc7455a0880f.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Сущности — Пространство имён XBSL: Std](entities-7b2acb4f9eee.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [Сущность.Объект](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/Entity.Object_ru/).
