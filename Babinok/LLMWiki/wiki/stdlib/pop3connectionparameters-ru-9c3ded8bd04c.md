# ПараметрыПодключенияPop3

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [pop3connectionparameters-ru-9c3ded8bd04c-3b62e9dc1ca0b8ad](../../raw/text-10.0/pop3connectionparameters-ru-9c3ded8bd04c-3b62e9dc1ca0b8ad.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Email.

Имена для поиска: `ПараметрыПодключенияPop3`, `Pop3ConnectionParameters`, `Стд::ЭлектроннаяПочта::ПараметрыПодключенияPop3`, `Std::Email::Pop3ConnectionParameters`.

## Обзор

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](emailconnectionparameters-ru-a1466a61e9ac.md)

## Документированный контракт и примеры

`Стд::ЭлектроннаяПочта::ПараметрыПодключенияPop3` `Доступность: Сервер`

Параметры приема почты.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](emailconnectionparameters-ru-a1466a61e9ac.md)

---

## Конструкторы

### ПараметрыПодключенияPop3

`Доступность: Сервер`

```
ПараметрыПодключенияPop3(
  Сервер: Строка,
  Port: Число = 995,
  Аутентификация: АутентификацияПочты,
  ПараметрыЗащиты: ПараметрыЗащищенногоСоединения)
```

Конструктор параметров подключения к серверу электронной почты с сервером

`Сервер`

, портом

`Port`

, аутентификацией

`Аутентификация`

и параметрами защиты

`ПараметрыЗащиты`

.

#### Исключения

**[ИсключениеНедопустимыйАргумент](illegalargumentexception-ru-fc532bf88932.md)** - Если сервер указан пустой строкой или порт не из диапазона (0, 65535) или.

---

## Свойства

### ПараметрыЗащиты

`Доступность: Сервер`

```
ПараметрыЗащиты: ПараметрыЗащищенногоСоединения
```

Параметры безопасного соединения с почтовым сервером. По-умолчанию используются сертификаты системы.

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## Список унаследованных свойств

### ПараметрыПодключенияПочты

[Аутентификация](emailconnectionparameters-ru-a1466a61e9ac.md), [ИспользоватьSsl](emailconnectionparameters-ru-a1466a61e9ac.md), [Порт](emailconnectionparameters-ru-a1466a61e9ac.md), [РазрешитьStartTls](emailconnectionparameters-ru-a1466a61e9ac.md), [Сервер](emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутПередачиДанных](emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутСоединения](emailconnectionparameters-ru-a1466a61e9ac.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Стд::ЭлектроннаяПочта — Пространство имён XBSL: Std](email-b3c1b4615997.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [ПараметрыПодключенияPop3](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/Pop3ConnectionParameters_ru/).
