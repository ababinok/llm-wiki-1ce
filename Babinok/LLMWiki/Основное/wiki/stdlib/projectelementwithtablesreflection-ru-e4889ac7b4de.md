# ОтражениеЭлементаПроектаСТаблицами

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [projectelementwithtablesreflection-ru-e4889ac7b4de-c5d65df045b632fb](../../raw/text-10.0/projectelementwithtablesreflection-ru-e4889ac7b4de-c5d65df045b632fb.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеЭлементаПроектаСТаблицами`, `ProjectElementWithTablesReflection`, `Стд::Отражение::ОтражениеЭлементаПроектаСТаблицами`, `Std::Reflection::ProjectElementWithTablesReflection`.

## Обзор

Описание элемента проекта с таблицами

## Документированный контракт и примеры

`Стд::Отражение::ОтражениеЭлементаПроектаСТаблицами` `Доступность: Сервер`

Описание элемента проекта с таблицами

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ОтражениеЭлементаПроекта](projectelementreflection-ru-20a73ff0cc46.md)

*Дочерние типы:* [ОтражениеЖурналаДанных](datajournalreflection-ru-f431745adae8.md), [ОтражениеСущности](../data/entityreflection-ru-63409aa370d3.md), [ОтражениеЭлементаПроектаВиртуальнаяТаблица](virtualtableprojectelementreflection-ru-0137a63e58e8.md), [ОтражениеЭлементаПроектаКонтрактСущности](../data/entitycontractprojectelementreflection-ru-1e3621572b02.md)

---

## Свойства

### ОсновнаяТаблица

`Версия 8.0 и выше`

`Доступность: Сервер` `ТолькоЧтение`

```
ОсновнаяТаблица: ОтражениеТаблицы?
```

Основная таблица сущности. Значение `Неопределено`, если у данного элемента проекта нет основной таблицы.

---

### ОсновнаяТаблица

`Версия 7.0 и ниже`

> **Исторический контракт:** верхняя граница версии 7.0; не используйте этот член для 10.0.


`Доступность: Сервер` `ТолькоЧтение`

```
ОсновнаяТаблица: ОтражениеТаблицы
```

Свойство заменено на [ОсновнаяТаблица](projectelementwithtablesreflection-ru-e4889ac7b4de.md).

---

### ТаблицыБазыДанных

`Доступность: Сервер` `ТолькоЧтение`

```
ТаблицыБазыДанных: ЧитаемыйМассив<ОтражениеТаблицы>
```

Таблицы, порождаемые элементом проекта

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

[ПоТипу](projectelementreflection-ru-20a73ff0cc46.md)

## Список унаследованных свойств

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ОтражениеЭлементаПроектаСТаблицами](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ProjectElementWithTablesReflection_ru/).
