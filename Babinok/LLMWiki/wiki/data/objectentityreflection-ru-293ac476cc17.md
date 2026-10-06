# ОтражениеОбъектнойСущности

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [objectentityreflection-ru-293ac476cc17-da5c84db435dc9ed](../../raw/text-10.0/objectentityreflection-ru-293ac476cc17-da5c84db435dc9ed.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеОбъектнойСущности`, `ObjectEntityReflection`, `Стд::Отражение::ОтражениеОбъектнойСущности`, `Std::Reflection::ObjectEntityReflection`.

## Обзор

Описание элемента проекта, являющегося источником объектных сущностей.

## Документированный контракт и примеры

`Стд::Отражение::ОтражениеОбъектнойСущности` `Доступность: Сервер`

Описание элемента проекта, являющегося источником объектных сущностей. Предоставляет информацию, специфичную для объектных сущностей

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [ОтражениеСущности](entityreflection-ru-63409aa370d3.md), [ОтражениеЭлементаПроекта](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

*Дочерние типы:* [ОтражениеОбъектнойСущностиСИерархиями](objectentitywithhierarchiesreflection-ru-4543015e7dc6.md)

---

## Свойства

### Реквизиты

`Доступность: Сервер` `ТолькоЧтение`

```
Реквизиты: ЧитаемыйМассив<ОтражениеХранимогоСвойства>
```

Реквизиты сущности

---

### ТабличныеЧасти

`Доступность: Сервер` `ТолькоЧтение`

```
ТабличныеЧасти: ЧитаемыйМассив<ОтражениеТабличнойЧастиСущности>
```

Табличные части сущности

---

### ТипДанные

`Доступность: Сервер` `ТолькоЧтение`

```
ТипДанные: Тип
```

Тип слепка данных конкретной сущности

---

### ТипОбъект

`Доступность: Сервер` `ТолькоЧтение`

```
ТипОбъект: Тип
```

Тип объекта конкретной сущности

---

### ТипПараметрыЗаписи

`Доступность: Сервер` `ТолькоЧтение`

```
ТипПараметрыЗаписи: Тип
```

Тип ПараметрыЗаписи для конкретной сущности

---

### ТипПараметрыУдаления

`Доступность: Сервер` `ТолькоЧтение`

```
ТипПараметрыУдаления: Тип
```

Тип ПараметрыУдаления для конкретной сущности

---

### ТипСсылка

`Доступность: Сервер` `ТолькоЧтение`

```
ТипСсылка: Тип
```

Тип ссылки конкретной сущности

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

### ОтражениеСущности

[ОсновнаяТаблица](entityreflection-ru-63409aa370d3.md), [ТипОдиночка](entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ОсновнаяТаблица](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md), [ТаблицыБазыДанных](../stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## See Also

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](../stdlib/reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [ОтражениеОбъектнойСущности](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ObjectEntityReflection_ru/).
