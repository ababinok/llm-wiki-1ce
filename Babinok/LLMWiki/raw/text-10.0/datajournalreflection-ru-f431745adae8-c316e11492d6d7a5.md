# ОтражениеЖурналаДанных

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/DataJournalReflection_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Reflection/DataJournalReflection_ru/index.html
> SHA256: 093c58836dc2ceb658525c81b474abd35486fb9d5185284baa0fac4f7e92bf7c
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Отражение::ОтражениеЖурналаДанных` `Доступность: Сервер`

Описание элемента проекта "ЖурналДанных".

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОтражениеЭлементаПроекта](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

---

## Свойства

### Колонки

`Доступность: Сервер` `ТолькоЧтение`

```
Колонки: ЧитаемыйМассив<ОтражениеКолонкиЖурналаДанных>
```

Отражения колонок конкретного журнала.

---

### ТипКлючЗаписи

`Доступность: Сервер` `ТолькоЧтение`

```
ТипКлючЗаписи: Тип
```

Тип ключа записи конкретного журнала.

---

### ТипОдиночка

`Доступность: Сервер` `ТолькоЧтение`

```
ТипОдиночка: Тип<Одиночка>
```

Тип одиночки конкретного журнала.

---

## Методы

### ПоТипу

`Доступность: Сервер` `Статический`

```
ПоТипу(Тип: Тип): ОтражениеЖурналаДанных
```

Статический метод. Позволяет получить отражение журнала по типу, порожденному элементом проекта

`ЖурналДанных`

. Если переданный тип не является типом порожденным журналом, будет выброшено

`ИсключениеОтражения`

.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ОтражениеЭлементаПроекта

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[ПоТипу](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md) [(Переопределение)](../../wiki/stdlib/datajournalreflection-ru-f431745adae8.md)

## Список унаследованных свойств

### ОтражениеЭлементаПроекта

[ВидЭлемента](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ОсновнаяТаблица](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md), [ТаблицыБазыДанных](../../wiki/stdlib/projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)
