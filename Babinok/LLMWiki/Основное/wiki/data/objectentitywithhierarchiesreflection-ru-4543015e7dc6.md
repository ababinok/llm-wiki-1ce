# ОтражениеОбъектнойСущностиСИерархиями

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [objectentitywithhierarchiesreflection-ru-4543015e7dc6-00b55f7d69337774](../../raw/text-10.0/objectentitywithhierarchiesreflection-ru-4543015e7dc6-00b55f7d69337774.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеОбъектнойСущностиСИерархиями`, `ObjectEntityWithHierarchiesReflection`, `Стд::Отражение::ОтражениеОбъектнойСущностиСИерархиями`, `Std::Reflection::ObjectEntityWithHierarchiesReflection`.

## Обзор

Описание элемента проекта, являющегося источником объектных сущностей, с иерархиями.

## Документированный контракт и примеры

`Версия 9.0 и выше`

`Стд::Отражение::ОтражениеОбъектнойСущностиСИерархиями` `Доступность: Сервер`

Описание элемента проекта, являющегося источником объектных сущностей, с иерархиями.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [ОтражениеОбъектнойСущности](objectentityreflection-ru-293ac476cc17.md), [ОтражениеСущности](entityreflection-ru-63409aa370d3.md), [ОтражениеЭлементаПроекта](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

*Дочерние типы:* [ОтражениеСправочника](catalogreflection-ru-ba007c3db518.md)

---

## Свойства

### ВидИерархии

`Доступность: Сервер` `ТолькоЧтение`

```
ВидИерархии: Перечисление?
```

Вид иерархии элемента проекта.

---

### Иерархии

`Доступность: Сервер` `ТолькоЧтение`

```
Иерархии: ЧитаемыйМассив<ОтражениеИерархии>
```

Список иерархий элемента проекта.

---

### Иерархический

`Доступность: Сервер` `ТолькоЧтение`

```
Иерархический: Булево
```

Признак иерархичности элемента проекта.

---

### ИерархияПоУмолчанию

`Доступность: Сервер` `ТолькоЧтение`

```
ИерархияПоУмолчанию: ОтражениеИерархии?
```

Иерархия по умолчанию для элемента проекта.

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

### ОтражениеСущности

[ОсновнаяТаблица](entityreflection-ru-63409aa370d3.md), [ТипОдиночка](entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеСущности

[ОсновнаяТаблица](entityreflection-ru-63409aa370d3.md), [ТипОдиночка](entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## See Also

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](../stdlib/reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [ОтражениеОбъектнойСущностиСИерархиями](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ObjectEntityWithHierarchiesReflection_ru/).
