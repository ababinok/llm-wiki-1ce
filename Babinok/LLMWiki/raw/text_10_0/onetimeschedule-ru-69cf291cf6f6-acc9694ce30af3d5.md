# ОднократноеРасписание

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Schedules/OneTimeSchedule_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Schedules/OneTimeSchedule_ru/index.html
> SHA256: 64c1ea045bbf96fc242f566a1d8d0b31e2a8b630bdd27fee4d2cb6dcd6a5ce80
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Расписания::ОднократноеРасписание` `Доступность: КлиентИСервер`

Расписание однократного запуска в указанный момент. Создается через методы объекта [Расписание](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md).

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Расписание](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

---

## Примеры

**Общие примеры**

```xbsl
// Расписание запуска один раз в 8 утра 18 июня 2021 или сразу после запуска, если в этот момент система не работала.
знч Разово = Расписание.Однократно(Момент{2021-06-18 8:00 Z}, ИсполнятьПропущенное = Истина)
    
пер Задание = ЗапланированныеЗадания.Создать(&МойМодуль.МойМетод)
Задание.Настроить(Ключ = "МоеЗадание", Расписание = Разово)
Задание.Запланировать()
```

---

## Свойства

### ЗапуститьВ

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ЗапуститьВ: Момент
```

Момент запуска задания.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### Расписание

[Ежедневно](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

[Ежемесячно](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

[Ежемесячно](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

[Еженедельно](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

[МоментСледующегоИсполнения](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

[Однократно](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

[Периодическое](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

## Список унаследованных свойств

### Расписание

[ВремяКонца](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md), [ВремяНачала](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md), [ИсполнятьПропущенное](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)
