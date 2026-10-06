# ПараметрДинамическогоСписка

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/DataSources/DynamicList/DynamicListParameter_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/DataSources/DynamicList/DynamicListParameter_ru/index.html
> SHA256: 3758be6a79a6c8fba8748461f0a95ee6221a42eec33f1682a3f2a3933e6f7f4e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ИсточникиДанных::ДинамическийСписок::ПараметрДинамическогоСписка` `Доступность: КлиентИСервер`

Параметр динамического списка. Определяет значение параметра используемого в выражениях в [ПолеДинамическогоСписка](../../wiki/interface/dynamiclistfield-ru-123b2f37f3d2.md), [ЭлементФильтраВыражение](../../wiki/interface/filteritemexpression-ru-2253b5a4a6ee.md), [АргументТаблицыВыражение](../../wiki/interface/tableargumentexpression-ru-af4277dd661e.md).

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### ПараметрДинамическогоСписка

`Доступность: КлиентИСервер`

```
ПараметрДинамическогоСписка(
  Значение: Объект?,
  Имя: Строка)
```

Создает параметр с указанными значениями полей.

---

## Свойства

### Значение

`Доступность: КлиентИСервер`

```
Значение: Объект?
```

Значение параметра.

---

### Имя

`Доступность: КлиентИСервер`

```
Имя: Строка
```

Имя параметра для подстановки в выражение.

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/interface/dynamiclistparameter-ru-0437a7bdc276.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
