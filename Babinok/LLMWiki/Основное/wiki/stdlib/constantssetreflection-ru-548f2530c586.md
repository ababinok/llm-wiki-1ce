# ОтражениеНабораКонстант

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [constantssetreflection-ru-548f2530c586-bb2ab49f1ef1e0e6](../../raw/text_10_0/constantssetreflection-ru-548f2530c586-bb2ab49f1ef1e0e6.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеНабораКонстант`, `ConstantsSetReflection`, `Стд::Отражение::ОтражениеНабораКонстант`, `Std::Reflection::ConstantsSetReflection`.

## Обзор

Описание элемента проекта, являющегося сущностью набора констант.

## Документированный контракт и примеры

`Стд::Отражение::ОтражениеНабораКонстант` `Доступность: Сервер`

Описание элемента проекта, являющегося сущностью набора констант. Предоставляет информацию, специфичную для наборов констант

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ОтражениеСущности](../data/entityreflection-ru-63409aa370d3.md), [ОтражениеЭлементаПроекта](projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](projectelementwithtablesreflection-ru-e4889ac7b4de.md)

---

## Свойства

### Константы

`Доступность: Сервер` `ТолькоЧтение`

```
Константы: ЧитаемыйМассив<ОтражениеХранимогоСвойства>
```

Список констант набора констант

---

### Периодичность

`Доступность: Сервер` `ТолькоЧтение`

```
Периодичность: ПериодичностьНабораКонстант
```

Периодичность набора констант

---

### ТипЗапись

`Доступность: Сервер` `ТолькоЧтение`

```
ТипЗапись: Тип?
```

Тип записи набора констант

---

### ТипКлючЗаписи

`Доступность: Сервер` `ТолькоЧтение`

```
ТипКлючЗаписи: Тип?
```

Тип ключа записи набора констант

---

### ТипПараметрыЗаписи

`Доступность: Сервер` `ТолькоЧтение`

```
ТипПараметрыЗаписи: Тип?
```

Тип ПараметрыЗаписи для набора констант

---

### ТипПараметрыУдаления

`Доступность: Сервер` `ТолькоЧтение`

```
ТипПараметрыУдаления: Тип?
```

Тип ПараметрыУдаления для набора констант

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

### ОтражениеСущности

[ПоТипу](../data/entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[НайтиВсе](projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](projectelementreflection-ru-20a73ff0cc46.md)

## Список унаследованных свойств

### ОтражениеСущности

[ОсновнаяТаблица](../data/entityreflection-ru-63409aa370d3.md), [ТипОдиночка](../data/entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ОсновнаяТаблица](projectelementwithtablesreflection-ru-e4889ac7b4de.md), [ТаблицыБазыДанных](projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ОтражениеНабораКонстант](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ConstantsSetReflection_ru/).
