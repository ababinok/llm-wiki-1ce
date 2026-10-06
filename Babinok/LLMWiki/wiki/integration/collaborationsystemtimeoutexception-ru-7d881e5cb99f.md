# ИсключениеТаймаутаСистемыВзаимодействия

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [collaborationsystemtimeoutexception-ru-7d881e5cb99f-cafc2c3a463dd4bf](../../raw/text-10.0/collaborationsystemtimeoutexception-ru-7d881e5cb99f-cafc2c3a463dd4bf.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / CollaborationSystem.

Имена для поиска: `ИсключениеТаймаутаСистемыВзаимодействия`, `CollaborationSystemTimeoutException`, `Стд::СистемаВзаимодействия::ИсключениеТаймаутаСистемыВзаимодействия`, `Std::CollaborationSystem::CollaborationSystemTimeoutException`.

## Обзор

Исключение, выбрасываемое если вышел тайм-аут ожидания ответа от системы взаимодействия.

## Документированный контракт и примеры

`Стд::СистемаВзаимодействия::ИсключениеТаймаутаСистемыВзаимодействия` `Доступность: Сервер`

Исключение, выбрасываемое если вышел тайм-аут ожидания ответа от системы взаимодействия.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../stdlib/exception-ru-ed2632721976.md), [ИсключениеСистемыВзаимодействия](collaborationsystemexception-ru-f8d82f9023f2.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

```xbsl
знч ИдОбсуждения = Ууид{363c77c3-e0be-4d8a-bb0f-5fb47aa79f41}
знч Таймаут = 5с

пер Обсуждение: ОбсуждениеВзаимодействия?
попытка
    Обсуждение = СистемаВзаимодействия.НайтиОбсуждение(ИдОбсуждения, Таймаут)
поймать Исключение: ИсключениеТаймаутаСистемыВзаимодействия
    // логика обработки исключения
;     
```

---

## Список унаследованных методов

### Исключение

[ВСтроку](../stdlib/exception-ru-ed2632721976.md)

[Информация](../stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../stdlib/exception-ru-ed2632721976.md), [Описание](../stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../stdlib/exception-ru-ed2632721976.md), [Причина](../stdlib/exception-ru-ed2632721976.md)

## Список унаследованных событий

### Исключение

[Ид](../stdlib/exception-ru-ed2632721976.md), [Описание](../stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../stdlib/exception-ru-ed2632721976.md), [Причина](../stdlib/exception-ru-ed2632721976.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::СистемаВзаимодействия — Пространство имён XBSL: Std](collaborationsystem-a87edf727e1d.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ИсключениеТаймаутаСистемыВзаимодействия](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemTimeoutException_ru/).
