# ОтражениеЖурналаДанных

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [datajournalreflection-ru-f431745adae8-c316e11492d6d7a5](../../raw/text-10.0/datajournalreflection-ru-f431745adae8-c316e11492d6d7a5.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеЖурналаДанных`, `DataJournalReflection`, `Стд::Отражение::ОтражениеЖурналаДанных`, `Std::Reflection::DataJournalReflection`.

## Обзор

Описание элемента проекта "ЖурналДанных".

## Документированный контракт и примеры

`Стд::Отражение::ОтражениеЖурналаДанных` `Доступность: Сервер`

Описание элемента проекта "ЖурналДанных".

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ОтражениеЭлементаПроекта](projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСТаблицами](projectelementwithtablesreflection-ru-e4889ac7b4de.md)

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

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

### ОтражениеЭлементаПроекта

[НайтиВсе](projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](projectelementreflection-ru-20a73ff0cc46.md)

[ПоТипу](projectelementreflection-ru-20a73ff0cc46.md) [(Переопределение)](datajournalreflection-ru-f431745adae8.md)

## Список унаследованных свойств

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСТаблицами

[ОсновнаяТаблица](projectelementwithtablesreflection-ru-e4889ac7b4de.md), [ТаблицыБазыДанных](projectelementwithtablesreflection-ru-e4889ac7b4de.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ОтражениеЖурналаДанных](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/DataJournalReflection_ru/).
