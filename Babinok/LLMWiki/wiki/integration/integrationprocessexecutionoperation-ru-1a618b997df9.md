# ОперацияВыполнениеПроцессаИнтеграции

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationprocessexecutionoperation-ru-1a618b997df9-7d994d7bed439540](../../raw/text-10.0/integrationprocessexecutionoperation-ru-1a618b997df9-7d994d7bed439540.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / IntegrationBus / Events.

Имена для поиска: `ОперацияВыполнениеПроцессаИнтеграции`, `IntegrationProcessExecutionOperation`, `Стд::ИнтеграционнаяШина::События::ОперацияВыполнениеПроцессаИнтеграции`, `Std::IntegrationBus::Events::IntegrationProcessExecutionOperation`.

## Обзор

Операция, начало которой регистрируется в начале запуска процесса интеграции.

## Документированный контракт и примеры

`Стд::ИнтеграционнаяШина::События::ОперацияВыполнениеПроцессаИнтеграции` `Доступность: Сервер`

Операция, начало которой регистрируется в начале запуска процесса интеграции. Конец регистрируется при остановке процесса интеграции. В случае любой ошибки, возникшей при запуске или остановке, операция будет завершена с ошибкой.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../stdlib/eventlogevent-ru-928cb9b58d56.md)

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

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

### Представляемое

### СобытиеЖурналаСобытий

[ПолучитьСвойство](../stdlib/eventlogevent-ru-928cb9b58d56.md)

[Представление](../stdlib/eventlogevent-ru-928cb9b58d56.md)

## Список унаследованных свойств

### СобытиеЖурналаСобытий

[Важность](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ВидСобытия](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Длительность](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Ид](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ИдОшибки](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Имя](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ИнформацияОВнутреннемИсключении](../stdlib/eventlogevent-ru-928cb9b58d56.md), [КонецОперации](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Момент](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Операции](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Описание](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ОписанияСвойств](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Родитель](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Свойства](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Успешно](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ХарактерОшибки](../stdlib/eventlogevent-ru-928cb9b58d56.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::ИнтеграционнаяШина::События — Пространство имён XBSL: Std / IntegrationBus](events-0eccf43873da.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ОперацияВыполнениеПроцессаИнтеграции](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessExecutionOperation_ru/).
