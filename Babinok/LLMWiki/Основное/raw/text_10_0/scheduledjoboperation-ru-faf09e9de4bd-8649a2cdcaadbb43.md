# ОперацияЗапланированногоЗадания

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Jobs/Events/ScheduledJobOperation_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Jobs/Events/ScheduledJobOperation_ru/index.html
> SHA256: 225b4b254fec77c0516753b31f4cb01d2c812bd992c0932cc8abbb25329d5188
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Задания::События::ОперацияЗапланированногоЗадания` `Доступность: Сервер`

Операция, начало которой регистрируется вместе с началом выполнения запланированного задания. Конец операции регистрируется при окончании выполнения запланированного задания. В случае возникновения ошибки при выполнении задания будет зарегистрирован конец операции с ошибкой.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### ИдОшибочногоСобытия

`Доступность: Сервер` `ТолькоЧтение`

```
ИдОшибочногоСобытия: Ууид?
```

Идентификатор события ошибки, возникшей при выполнении операции.

---

### КлючЗадания

`Доступность: Сервер` `ТолькоЧтение`

```
КлючЗадания: Строка?
```

Ключ отслеживаемого задания.

---

### ПричинаОшибочногоЗавершенияОперации

`Доступность: Сервер` `ТолькоЧтение`

```
ПричинаОшибочногоЗавершенияОперации: Строка?
```

Причина ошибочного завершения операции.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Представляемое

### СобытиеЖурналаСобытий

[ПолучитьСвойство](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

[Представление](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

## Список унаследованных свойств

### СобытиеЖурналаСобытий

[Важность](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ВидСобытия](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Длительность](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Ид](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ИдОшибки](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Имя](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ИнформацияОВнутреннемИсключении](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [КонецОперации](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Момент](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Операции](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Описание](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ОписанияСвойств](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Родитель](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Свойства](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Успешно](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ХарактерОшибки](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)
