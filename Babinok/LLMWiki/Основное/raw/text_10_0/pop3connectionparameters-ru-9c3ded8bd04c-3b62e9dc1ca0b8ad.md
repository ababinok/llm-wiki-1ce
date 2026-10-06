# ПараметрыПодключенияPop3

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/Pop3ConnectionParameters_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Email/Pop3ConnectionParameters_ru/index.html
> SHA256: 7cfbc3ccb8af5e19615b1fcaba8171b350002109a8e48119b5d29ac70ba9e0aa
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ЭлектроннаяПочта::ПараметрыПодключенияPop3` `Доступность: Сервер`

Параметры приема почты.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ПараметрыПодключенияПочты](../../wiki/stdlib/emailconnectionparameters-ru-a1466a61e9ac.md)

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
