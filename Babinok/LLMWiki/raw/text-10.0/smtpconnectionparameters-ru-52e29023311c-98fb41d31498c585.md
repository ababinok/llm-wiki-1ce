# ПараметрыПодключенияSmtp

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/SmtpConnectionParameters_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Email/SmtpConnectionParameters_ru/index.html
> SHA256: e80b70bd3ce9778ad9c770a553de5f81fecd3647e5db1edc88cb6accd41c7763
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ЭлектроннаяПочта::ПараметрыПодключенияSmtp` `Доступность: Сервер`

Параметры подключения к серверу электронной почты для отправки писем.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)

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

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - Если сервер указан пустой строкой или порт не из диапазона (0, 65535) или.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ПараметрыПодключенияПочты

[Аутентификация](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ИспользоватьSsl](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [Порт](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [РазрешитьStartTls](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [Сервер](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутПередачиДанных](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутСоединения](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)
