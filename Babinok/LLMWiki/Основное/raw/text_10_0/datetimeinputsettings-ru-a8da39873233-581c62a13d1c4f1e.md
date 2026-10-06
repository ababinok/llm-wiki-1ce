# НастройкиВводаДатыВремени

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/DataInput/DateTimeInputSettings_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/DataInput/DateTimeInputSettings_ru/index.html
> SHA256: 34691fb999d7f68adcb1f36e5dd20c90f8c46f39ffa90224b211a3c9d9f259c1
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ВводДанных::НастройкиВводаДатыВремени` `Доступность: КлиентИСервер`

Содержит настройки для ввода даты и времени.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### НастройкиВводаДатыВремени

`Доступность: КлиентИСервер`

```
НастройкиВводаДатыВремени(
  ССекундами: Авто|Булево,
  ШагИзменения: Авто|Число)
```

Создает новый объект

[НастройкиВводаДатыВремени](../../wiki/interface/datetimeinputsettings-ru-a8da39873233.md)

---

## Свойства

### ССекундами

`Доступность: КлиентИСервер`

```
ССекундами: Авто|Булево
```

Включает ввод секунд при вводе времени.

---

### ШагИзменения

`Доступность: КлиентИСервер`

```
ШагИзменения: Авто|Число
```

Устанавливает шаг изменения единицы времени при нажатии на кнопки регулирования значения.

Для типов: [Дата](../../wiki/stdlib/date-ru-d160dc00114c.md) и [ДатаВремя](../../wiki/stdlib/datetime-ru-b9ec40d17fe0.md), [Момент](../../wiki/stdlib/instant-ru-09dd46b34eb4.md) - в днях. Для типа [Время](../../wiki/stdlib/time-ru-bbaed59a0dcd.md) - в часах.

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

Строковое представление объекта.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/interface/datetimeinputsettings-ru-a8da39873233.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
