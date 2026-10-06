# ОтражениеСущностиРегистра

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/RegisterEntityReflection_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Reflection/RegisterEntityReflection_ru/index.html
> SHA256: 60d323fc1989b4e7120666ac331ec22458d69372a35c0a2cba88737ee1085510
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Отражение::ОтражениеСущностиРегистра` `Доступность: Сервер`

Описание элемента проекта, являющегося сущностью регистра. Предоставляет информацию, специфичную для регистров

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОтражениеСущности](../../wiki/data/entityreflection-ru-63409aa370d3.md), [ОтражениеЭлементаПроекта](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

---

## Свойства

### Измерения

`Доступность: Сервер` `ТолькоЧтение`

```
Измерения: ЧитаемыйМассив<ОтражениеХранимогоСвойства>
```

Список измерений регистра. Для периодических регистров включает в себя Период

---

### ПодчинениеРегистратору

`Доступность: Сервер` `ТолькоЧтение`

```
ПодчинениеРегистратору: Булево
```

Признак того, что регистр является подчиненным документу-регистратору

---

### Реквизиты

`Доступность: Сервер` `ТолькоЧтение`

```
Реквизиты: ЧитаемыйМассив<ОтражениеХранимогоСвойства>
```

Список реквизитов регистра

---

### Ресурсы

`Доступность: Сервер` `ТолькоЧтение`

```
Ресурсы: ЧитаемыйМассив<ОтражениеХранимогоСвойства>
```

Список ресурсов регистра

---

### ТипЗапись

`Доступность: Сервер` `ТолькоЧтение`

```
ТипЗапись: Тип
```

Тип записи регистра

---

### ТипКлючЗаписи

`Доступность: Сервер` `ТолькоЧтение`

```
ТипКлючЗаписи: Тип
```

Тип ключа записи регистра

---

### ТипНаборЗаписей

`Доступность: Сервер` `ТолькоЧтение`

```
ТипНаборЗаписей: Тип
```

Тип набора записей регистра

---

### ТипНаборЗаписейФильтр

`Доступность: Сервер` `ТолькоЧтение`

```
ТипНаборЗаписейФильтр: Тип
```

Тип фильтра набора записей регистра

---

### ТипПараметрыЗаписи

`Доступность: Сервер` `ТолькоЧтение`

```
ТипПараметрыЗаписи: Тип
```

Тип ПараметрыЗаписи для регистра

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ОтражениеСущности

[ПоТипу](../../wiki/data/entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

## Список унаследованных свойств

### ОтражениеСущности

[ОсновнаяТаблица](../../wiki/data/entityreflection-ru-63409aa370d3.md), [ТипОдиночка](../../wiki/data/entityreflection-ru-63409aa370d3.md)

### ОтражениеЭлементаПроекта

[ВидЭлемента](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ТаблицыБазыДанных](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ОсновнаяТаблица](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md), [ТаблицыБазыДанных](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)
