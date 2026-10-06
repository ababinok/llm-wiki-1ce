# ОтражениеСправочника

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [catalogreflection-ru-ba007c3db518-e7c488d8d28341c0](../../raw/text-10.0/catalogreflection-ru-ba007c3db518-e7c488d8d28341c0.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Catalogs / Reflection.

Имена для поиска: `ОтражениеСправочника`, `CatalogReflection`, `Стд::Справочники::Отражение::ОтражениеСправочника`, `Std::Catalogs::Reflection::CatalogReflection`.

## Обзор

Описание элемента проекта Справочник.

## Документированный контракт и примеры

`Стд::Справочники::Отражение::ОтражениеСправочника` `Доступность: Сервер`

Описание элемента проекта Справочник.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [ОтражениеОбъектнойСущности](objectentityreflection-ru-293ac476cc17.md), [ОтражениеОбъектнойСущностиСИерархиями](objectentitywithhierarchiesreflection-ru-4543015e7dc6.md), [ОтражениеСущности](entityreflection-ru-63409aa370d3.md), [ОтражениеЭлементаПроекта](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

---

## Свойства

### ВидИерархии

`Доступность: Сервер` `ТолькоЧтение`

```
ВидИерархии: ВидИерархииСправочника?
```

Вид иерархии справочника.

Переопределение: [ВидИерархии](catalogreflection-ru-ba007c3db518.md)

---

### Иерархии

`Доступность: Сервер` `ТолькоЧтение`

```
Иерархии: ЧитаемыйМассив<ОтражениеИерархииСправочника>
```

Список иерархий справочника.

Переопределение: [Иерархии](catalogreflection-ru-ba007c3db518.md)

---

### ИерархияПоУмолчанию

`Доступность: Сервер` `ТолькоЧтение`

```
ИерархияПоУмолчанию: ОтражениеИерархииСправочника?
```

Иерархия по умолчанию для справочника.

Переопределение: [ИерархияПоУмолчанию](catalogreflection-ru-ba007c3db518.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

### ОтражениеСущности

[ПоТипу](entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[НайтиВсе](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

## Список унаследованных свойств

### ОтражениеОбъектнойСущности

[Реквизиты](objectentityreflection-ru-293ac476cc17.md), [ТабличныеЧасти](objectentityreflection-ru-293ac476cc17.md), [ТипДанные](objectentityreflection-ru-293ac476cc17.md), [ТипОбъект](objectentityreflection-ru-293ac476cc17.md), [ТипПараметрыЗаписи](objectentityreflection-ru-293ac476cc17.md), [ТипПараметрыУдаления](objectentityreflection-ru-293ac476cc17.md), [ТипСсылка](objectentityreflection-ru-293ac476cc17.md)

### ОтражениеОбъектнойСущностиСИерархиями

[Иерархический](objectentitywithhierarchiesreflection-ru-4543015e7dc6.md)

### ОтражениеСущности

[ОсновнаяТаблица](entityreflection-ru-63409aa370d3.md), [ТипОдиночка](entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеОбъектнойСущности

[Реквизиты](objectentityreflection-ru-293ac476cc17.md), [ТабличныеЧасти](objectentityreflection-ru-293ac476cc17.md), [ТипДанные](objectentityreflection-ru-293ac476cc17.md), [ТипОбъект](objectentityreflection-ru-293ac476cc17.md), [ТипПараметрыЗаписи](objectentityreflection-ru-293ac476cc17.md), [ТипПараметрыУдаления](objectentityreflection-ru-293ac476cc17.md), [ТипСсылка](objectentityreflection-ru-293ac476cc17.md)

### ОтражениеСущности

[ОсновнаяТаблица](entityreflection-ru-63409aa370d3.md), [ТипОдиночка](entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Справочники::Отражение — Пространство имён XBSL: Std / Catalogs](reflection-2aae26f59485.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [ОтражениеСправочника](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Catalogs/Reflection/CatalogReflection_ru/).
