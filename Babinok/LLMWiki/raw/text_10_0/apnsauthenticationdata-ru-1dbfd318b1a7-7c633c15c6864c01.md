# ДанныеАутентификацииApns

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/DeliverableNotifications/ApnsAuthenticationData_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/DeliverableNotifications/ApnsAuthenticationData_ru/index.html
> SHA256: 53f580d31e05ceec692e1a05b6cffb051d94faff682293626cd7f8025687ae0e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ДоставляемыеУведомления::ДанныеАутентификацииApns` `Доступность: Сервер`

Данные аутентификации для сервиса APNS (Apple Push Notifications Service)

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ДанныеАутентификацииДоставляемыхУведомлений](../../wiki/security/deliverablenotificationauthenticationdata-ru-a04a69680ee1.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### ДанныеАутентификацииApns

`Доступность: Сервер`

```
ДанныеАутентификацииApns(
  ИдПриложения: Строка,
  Сертификат: Байты,
  ПарольСертификата: Секрет|Строка)
```

Создает объект на основании сертификата и пароля к нему

---

## Свойства

### ПарольСертификата

`Версия 7.0 и ниже`

`Доступность: Сервер` `ТолькоЧтение`

```
ПарольСертификата: Строка
```

Пароль к сертификату APNS

---

### Сертификат

`Доступность: Сервер` `ТолькоЧтение`

```
Сертификат: Байты
```

Файл с сертификатом для APNS

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ДанныеАутентификацииДоставляемыхУведомлений

[ИдПриложения](../../wiki/security/deliverablenotificationauthenticationdata-ru-a04a69680ee1.md)
