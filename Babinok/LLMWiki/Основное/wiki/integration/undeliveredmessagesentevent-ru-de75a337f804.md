# СобытиеНедоставленноеСообщениеОтправлено

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [undeliveredmessagesentevent-ru-de75a337f804-8e2cf850997f6c01](../../raw/text-10.0/undeliveredmessagesentevent-ru-de75a337f804-8e2cf850997f6c01.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / IntegrationBus / Events.

Имена для поиска: `СобытиеНедоставленноеСообщениеОтправлено`, `UndeliveredMessageSentEvent`, `Стд::ИнтеграционнаяШина::События::СобытиеНедоставленноеСообщениеОтправлено`, `Std::IntegrationBus::Events::UndeliveredMessageSentEvent`.

## Обзор

Событие, регистрируемое при отправке недоставленного сообщения в узел процесса интеграции.

## Документированный контракт и примеры

`Стд::ИнтеграционнаяШина::События::СобытиеНедоставленноеСообщениеОтправлено` `Доступность: Сервер`

Событие, регистрируемое при отправке недоставленного сообщения в узел процесса интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### ИдСообщения

`Доступность: Сервер` `ТолькоЧтение`

```
ИдСообщения: Строка?
```

Идентификатор отправленного сообщения. Совпадает с идентификатором недоставленного сообщения.

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

Узел, в который было отправлено недоставленное сообщение.

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

Оригинал: [СобытиеНедоставленноеСообщениеОтправлено](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Events/UndeliveredMessageSentEvent_ru/).
