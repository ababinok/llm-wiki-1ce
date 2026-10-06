# HttpСервис

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [httpservice-ru-a5cc07d8bdea-ab24cdd650e47ce8](../../raw/text-10.0/httpservice-ru-a5cc07d8bdea-ab24cdd650e47ce8.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / HttpServices.

Имена для поиска: `HttpСервис`, `HttpService`, `Стд::HttpСервисы::HttpСервис`, `Std::HttpServices::HttpService`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Одиночка](../stdlib/singleton-ru-cb90fb36f1e3.md)

## Документированный контракт и примеры

`Стд::HttpСервисы::HttpСервис` `Доступность: Сервер`

Базовый тип Http-сервисов.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Одиночка](../stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПересчитатьРазрешенияДоступа

`Доступность: Сервер`

```
ПересчитатьРазрешенияДоступа()
```

Пересчитывает разрешения доступа для Http-сервиса.

#### Примеры

В примере пересчитываются разрешения доступа для всех Http-сервисов приложения.

```xbsl
для Сервис из HttpСервисы
    Сервис.ПересчитатьРазрешенияДоступа()
;
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::HttpСервисы — Пространство имён XBSL: Std](httpservices-a7d3ec06f975.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [HttpСервис](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HttpServices/HttpService_ru/).
