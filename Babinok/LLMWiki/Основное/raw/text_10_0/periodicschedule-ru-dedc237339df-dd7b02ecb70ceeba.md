# ПериодическоеРасписание

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Schedules/PeriodicSchedule_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Schedules/PeriodicSchedule_ru/index.html
> SHA256: 765c55ff0bf969c8e3426778c874bbe4f43a313215c641b2df42a275a9e84ab3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Расписания::ПериодическоеРасписание` `Доступность: КлиентИСервер`

Расписание постоянных запусков с указанным периодом. Создается через методы объекта [Расписание](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md).

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Расписание](../../wiki/stdlib/schedule-ru-f8ef0f9119e6.md)

---

## Примеры

**Общие примеры**

```xbsl
// Запуск задания через 3 секунды после окончания предыдущего запуска.
пер Задание = ЗапланированныеЗадания.Создать(&МойМодуль.МойМетод)
Задание.Настроить(Ключ = "МоеЗадание", Расписание = Расписание.Периодическое(3с))
Задание.Запланировать()
```

---

## Свойства

### Период

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Период: Длительность
```

Период времени, по истечении которого после окончания предыдущего запуска задание будет запущено снова.

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
