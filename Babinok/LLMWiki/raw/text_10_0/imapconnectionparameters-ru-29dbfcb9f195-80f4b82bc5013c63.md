# ПараметрыПодключенияImap

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/ImapConnectionParameters_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Email/ImapConnectionParameters_ru/index.html
> SHA256: 3126f42da900f5db981871812add4ac933bb61f38ff19eba09eaf90671ac4189
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ЭлектроннаяПочта::ПараметрыПодключенияImap` `Доступность: Сервер`

Параметры подключения к почтовому серверу по Imap.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)

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

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - Если сервер указан пустой строкой или порт не из диапазона (0, 65535) или.

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ПараметрыПодключенияПочты

[Аутентификация](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ИспользоватьSsl](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [Порт](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [РазрешитьStartTls](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [Сервер](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутПередачиДанных](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md), [ТаймаутСоединения](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)
