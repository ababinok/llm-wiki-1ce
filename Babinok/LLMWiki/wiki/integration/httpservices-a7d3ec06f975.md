# Стд::HttpСервисы

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [httpservices-a7d3ec06f975-d839acb930a059e4](../../raw/text-10.0/httpservices-a7d3ec06f975-d839acb930a059e4.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Пространство имён XBSL.

Владелец: Std.

Имена для поиска: `Стд::HttpСервисы`, `HttpServices`, `Std::HttpServices`.

## Обзор

Типы, обеспечивающие работу HTTP-сервисов.

## Документированный контракт и примеры

Типы, обеспечивающие работу HTTP-сервисов.

# Типы

## [HttpСервис](httpservice-ru-a5cc07d8bdea.md)

`Стд::HttpСервисы::HttpСервис` `Доступность: Сервер`

Базовый тип Http-сервисов.

---

## [HttpСервисЗапрос](httpservicerequest-ru-a05d6ed745e1.md)

`Стд::HttpСервисы::HttpСервисЗапрос` `Доступность: Сервер`

Запрос к HTTP-сервису. Экземпляр передается в параметре `Запрос` обработчика HTTP-сервиса.

---

## [HttpСервисОтвет](httpserviceresponse-ru-4509149859c4.md)

`Стд::HttpСервисы::HttpСервисОтвет` `Доступность: Сервер`

Результат выполнения обработчика HTTP-сервиса. Доступ к экземпляру осуществляется через свойство [Ответ](httpservicerequest-ru-a05d6ed745e1.md) параметра обработчика.

---

## [HttpСервисПраво](httpserviceprivilege-ru-2391af84c6f6.md)

`Стд::HttpСервисы::HttpСервисПраво` `Доступность: КлиентИСервер`

Право http-сервиса.

---

## [HttpСервисы](httpservices-ru-c3c21a436158.md)

`Стд::HttpСервисы::HttpСервисы` `Тип-одиночка` `Доступность: Сервер`

Http-сервисы.

---

## See Also

- [Навигатор раздела](overview.md)
- [Стд — Пространство имён XBSL: Std](../stdlib/std-c15458c2f5f0.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [Стд::HttpСервисы](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HttpServices/).
