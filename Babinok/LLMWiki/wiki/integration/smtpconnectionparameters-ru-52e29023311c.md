# ПараметрыПодключенияSmtp

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [smtpconnectionparameters-ru-52e29023311c-98fb41d31498c585](../../raw/text-10.0/smtpconnectionparameters-ru-52e29023311c-98fb41d31498c585.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Email.

Имена для поиска: `ПараметрыПодключенияSmtp`, `SmtpConnectionParameters`, `Стд::ЭлектроннаяПочта::ПараметрыПодключенияSmtp`, `Std::Email::SmtpConnectionParameters`.

## Обзор

Параметры подключения к серверу электронной почты для отправки писем.

## Документированный контракт и примеры

`Стд::ЭлектроннаяПочта::ПараметрыПодключенияSmtp` `Доступность: Сервер`

Параметры подключения к серверу электронной почты для отправки писем.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)

---

## Конструкторы

### ПараметрыПодключенияSmtp

`Доступность: Сервер`

```
ПараметрыПодключенияSmtp(
  Сервер: Строка,
  Port: Число = 465,
  Аутентификация: АутентификацияПочты)
```

Конструктор параметров подключения к серверу электронной почты с сервером

`Сервер`

, портом

`Port`

и аутентификацией

`Аутентификация`

.

#### Исключения

**[ИсключениеНедопустимыйАргумент](../stdlib/illegalargumentexception-ru-fc532bf88932.md)** - Если сервер указан пустой строкой или порт не из диапазона (0, 65535) или.

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ПараметрыПодключенияПочты

[Аутентификация](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ИспользоватьSsl](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [Порт](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [РазрешитьStartTls](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [Сервер](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутПередачиДанных](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутСоединения](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::ЭлектроннаяПочта — Пространство имён XBSL: Std](../stdlib/email-b3c1b4615997.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ПараметрыПодключенияSmtp](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/SmtpConnectionParameters_ru/).
