# ДанныеАутентификацииApns

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [apnsauthenticationdata-ru-1dbfd318b1a7-7c633c15c6864c01](../../raw/text_10_0/apnsauthenticationdata-ru-1dbfd318b1a7-7c633c15c6864c01.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / DeliverableNotifications.

Имена для поиска: `ДанныеАутентификацииApns`, `ApnsAuthenticationData`, `Стд::ДоставляемыеУведомления::ДанныеАутентификацииApns`, `Std::DeliverableNotifications::ApnsAuthenticationData`.

## Обзор

Данные аутентификации для сервиса APNS (Apple Push Notifications Service)

## Документированный контракт и примеры

`Стд::ДоставляемыеУведомления::ДанныеАутентификацииApns` `Доступность: Сервер`

Данные аутентификации для сервиса APNS (Apple Push Notifications Service)

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ДанныеАутентификацииДоставляемыхУведомлений](deliverablenotificationauthenticationdata-ru-a04a69680ee1.md), [Объект](../stdlib/object-ru-9e351f286699.md)

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

> **Исторический контракт:** верхняя граница версии 7.0; не используйте этот член для 10.0.


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

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ДанныеАутентификацииДоставляемыхУведомлений

[ИдПриложения](deliverablenotificationauthenticationdata-ru-a04a69680ee1.md)

## See Also

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::ДоставляемыеУведомления — Пространство имён XBSL: Std](../stdlib/deliverablenotifications-6ff659677735.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [ДанныеАутентификацииApns](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/DeliverableNotifications/ApnsAuthenticationData_ru/).
