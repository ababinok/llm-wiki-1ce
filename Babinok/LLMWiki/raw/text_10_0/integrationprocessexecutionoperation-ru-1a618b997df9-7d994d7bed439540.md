# ОперацияВыполнениеПроцессаИнтеграции

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessExecutionOperation_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessExecutionOperation_ru/index.html
> SHA256: cdacc48f99293ae49a9811942360f40447d0dae3d06510a46ca66b4a84f18661
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ИнтеграционнаяШина::События::ОперацияВыполнениеПроцессаИнтеграции` `Доступность: Сервер`

Операция, начало которой регистрируется в начале запуска процесса интеграции. Конец регистрируется при остановке процесса интеграции. В случае любой ошибки, возникшей при запуске или остановке, операция будет завершена с ошибкой.

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

### ПричинаОшибочногоЗавершенияОперации

`Доступность: Сервер` `ТолькоЧтение`

```
ПричинаОшибочногоЗавершенияОперации: Строка?
```

Причина ошибочного завершения операции.

---

### Процесс

`Доступность: Сервер` `ТолькоЧтение`

```
Процесс: Строка?
```

Процесс интеграции, в котором было зарегистрировано событие.

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
