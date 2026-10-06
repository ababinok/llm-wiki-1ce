# ОтражениеОбработки

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ProcessingReflection_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Reflection/ProcessingReflection_ru/index.html
> SHA256: fa522264398dd8ca3984857baf0769a681bfaf08b1d91f20416062b51b62942d
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Отражение::ОтражениеОбработки` `Доступность: Сервер`

Описание элемента проекта "Обработка".

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОтражениеЭлементаПроекта](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ОтражениеЭлементаПроектаСОперациями](../../wiki/stdlib/projectelementwithoperationsreflection-ru-4afd2675a68d.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ОтражениеЭлементаПроекта

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[НайтиВсе](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

[ПоТипу](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md) [(Переопределение)](../../wiki/stdlib/processingreflection-ru-f67b6c522dd2.md)

## Список унаследованных свойств

### ОтражениеЭлементаПроекта

[ВидЭлемента](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)

### ОтражениеЭлементаПроектаСОперациями

[Операции](../../wiki/stdlib/projectelementwithoperationsreflection-ru-4afd2675a68d.md), [ОсновнаяОперация](../../wiki/stdlib/projectelementwithoperationsreflection-ru-4afd2675a68d.md)

## Список унаследованных событий

### ОтражениеЭлементаПроекта

[ВидЭлемента](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Ид](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [Имя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md), [ПолноеИмя](../../wiki/stdlib/projectelementreflection-ru-20a73ff0cc46.md)
