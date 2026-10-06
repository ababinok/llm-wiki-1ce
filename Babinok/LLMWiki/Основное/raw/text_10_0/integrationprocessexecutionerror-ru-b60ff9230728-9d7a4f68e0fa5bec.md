# ОшибкаВыполненияПроцессаИнтеграции

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessExecutionError_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessExecutionError_ru/index.html
> SHA256: db9575a6c1a0323af85119806c95a2d8ab384e513d94b2c5e3bb6c0b099959bc
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ИнтеграционнаяШина::События::ОшибкаВыполненияПроцессаИнтеграции` `Доступность: Сервер`

Событие регистрируется при любой ошибке, возникающей при доставке сообщения процессом интеграции. Если ошибка связана с определенным узлом процесса, имя этого узла в свойстве Узел. Если ошибка связана с определенным маршрутом процесса, имя этого маршрута в свойстве Маршрут.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### Маршрут

`Доступность: Сервер` `ТолькоЧтение`

```
Маршрут: Строка?
```

Маршрут, в котором произошла ошибка. Если не указан, то ошибка произошла в узле.

---

### Ошибка

`Доступность: Сервер` `ТолькоЧтение`

```
Ошибка: Строка?
```

Текст ошибки

---

### Процесс

`Доступность: Сервер` `ТолькоЧтение`

```
Процесс: Строка?
```

Процесс интеграции, в котором было зарегистрировано событие.

---

### Узел

`Доступность: Сервер` `ТолькоЧтение`

```
Узел: Строка?
```

Узел, в котором произошла ошибка. Если не указан, то ошибка произошла в маршруте.

---

### Участник

`Доступность: Сервер` `ТолькоЧтение`

```
Участник: Строка?
```

Участник, у которого произошла ошибка.

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
