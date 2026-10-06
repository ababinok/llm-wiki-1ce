# ПараметрыПодключенияImap

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [imapconnectionparameters-ru-29dbfcb9f195-80f4b82bc5013c63](../../raw/text-10.0/imapconnectionparameters-ru-29dbfcb9f195-80f4b82bc5013c63.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Email.

Имена для поиска: `ПараметрыПодключенияImap`, `ImapConnectionParameters`, `Стд::ЭлектроннаяПочта::ПараметрыПодключенияImap`, `Std::Email::ImapConnectionParameters`.

## Обзор

Параметры подключения к почтовому серверу по Imap.

## Документированный контракт и примеры

`Стд::ЭлектроннаяПочта::ПараметрыПодключенияImap` `Доступность: Сервер`

Параметры подключения к почтовому серверу по Imap.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](../stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)

---

## Конструкторы

### ПараметрыПодключенияImap

`Доступность: Сервер`

```
ПараметрыПодключенияImap(
  Сервер: Строка,
  Порт: Число = 993,
  Аутентификация: АутентификацияПочты,
  ПараметрыЗащиты: ПараметрыЗащищенногоСоединения)
```

Конструктор параметров подключения к серверу электронной почты с сервером

`Сервер`

, портом

`Порт`

, аутентификацией

`Аутентификация`

и параметрами защиты

`ПараметрыЗащиты`

.

#### Исключения

**[ИсключениеНедопустимыйАргумент](../stdlib/illegalargumentexception-ru-fc532bf88932.md)** - Если сервер указан пустой строкой или порт не из диапазона (0, 65535) или.

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

Оригинал: [ПараметрыПодключенияImap](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/ImapConnectionParameters_ru/).
