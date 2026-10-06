# ИсключениеТаймаутаСистемыВзаимодействия

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemTimeoutException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemTimeoutException_ru/index.html
> SHA256: 4bdfb159f6d847a47d23c5e8afee49c7d571db21f0c52b8ad20954dc3e8cca03
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::СистемаВзаимодействия::ИсключениеТаймаутаСистемыВзаимодействия` `Доступность: Сервер`

Исключение, выбрасываемое если вышел тайм-аут ожидания ответа от системы взаимодействия.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [ИсключениеСистемыВзаимодействия](../../wiki/integration/collaborationsystemexception-ru-f8d82f9023f2.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

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

[ВСтроку](../../wiki/stdlib/exception-ru-ed2632721976.md)

[Информация](../../wiki/stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../../wiki/stdlib/exception-ru-ed2632721976.md), [Описание](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../../wiki/stdlib/exception-ru-ed2632721976.md), [Причина](../../wiki/stdlib/exception-ru-ed2632721976.md)

## Список унаследованных событий

### Исключение

[Ид](../../wiki/stdlib/exception-ru-ed2632721976.md), [Описание](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../../wiki/stdlib/exception-ru-ed2632721976.md), [Причина](../../wiki/stdlib/exception-ru-ed2632721976.md)
