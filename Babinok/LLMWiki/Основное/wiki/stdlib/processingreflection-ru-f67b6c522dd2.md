# ОтражениеОбработки

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [processingreflection-ru-f67b6c522dd2-ab54829ee9ff314d](../../raw/text-10.0/processingreflection-ru-f67b6c522dd2-ab54829ee9ff314d.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеОбработки`, `ProcessingReflection`, `Стд::Отражение::ОтражениеОбработки`, `Std::Reflection::ProcessingReflection`.

## Обзор

Описание элемента проекта "Обработка".

## Документированный контракт и примеры

`Стд::Отражение::ОтражениеОбработки` `Доступность: Сервер`

Описание элемента проекта "Обработка".

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ОтражениеЭлементаПроекта](projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСОперациями](projectelementwithoperationsreflection-ru-4afd2675a68d.md)

---

## Свойства

### Реквизиты

`Доступность: Сервер` `ТолькоЧтение`

```
Реквизиты: ЧитаемыйМассив<ОтражениеСвойства>
```

Реквизиты конкретной обработки.

---

### ТипКоманды

`Доступность: Сервер` `ТолькоЧтение`

```
ТипКоманды: Тип
```

Тип команд конкретной обработки.

---

### ТипОбъект

`Доступность: Сервер` `ТолькоЧтение`

```
ТипОбъект: Тип
```

Тип объекта конкретной обработки.

---

### ТипОдиночка

`Доступность: Сервер` `ТолькоЧтение`

```
ТипОдиночка: Тип<Одиночка>
```

Тип конкретной обработки.

---

## Методы

### ПоТипу

`Доступность: Сервер` `Статический`

```
ПоТипу(Тип: Тип): ОтражениеОбработки
```

Статический метод. Позволяет получить отражение обработки по типу, порожденному элементом проекта

`Обработка`

. Если переданный тип не является типом порожденным обработкой, будет выброшено

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

[ПоТипу](projectelementreflection-ru-20a73ff0cc46.md) [(Переопределение)](processingreflection-ru-f67b6c522dd2.md)

## Список унаследованных свойств

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСОперациями

[Операции](projectelementwithoperationsreflection-ru-4afd2675a68d.md), [ОсновнаяОперация](projectelementwithoperationsreflection-ru-4afd2675a68d.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](projectelementreflection-ru-20a73ff0cc46.md), [Ид](projectelementreflection-ru-20a73ff0cc46.md), [Имя](projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](projectelementreflection-ru-20a73ff0cc46.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ОтражениеОбработки](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ProcessingReflection_ru/).
