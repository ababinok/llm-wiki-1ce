# ДанныеАутентификацииHms

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/DeliverableNotifications/HmsAuthenticationData_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/DeliverableNotifications/HmsAuthenticationData_ru/index.html
> SHA256: 87af1ed44925ea96fae94c7521ce082fff23858489f1e5eb88a185255ed14a7f
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ДоставляемыеУведомления::ДанныеАутентификацииHms` `Доступность: Сервер`

Данные аутентификации для сервиса HMS (Huawei Messaging Service)

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ДанныеАутентификацииДоставляемыхУведомлений](../../wiki/security/deliverablenotificationauthenticationdata-ru-a04a69680ee1.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### ДанныеАутентификацииHms

`Доступность: Сервер`

```
ДанныеАутентификацииHms(
  ИдПриложения: Строка,
  ИдПроекта: Строка,
  ИдКлиента: Строка,
  СекретКлиента: Строка)
```

Создает объект на основании идентификатора проекта, клиента и секретного ключа

---

## Свойства

### ИдКлиента

`Доступность: Сервер` `ТолькоЧтение`

```
ИдКлиента: Строка
```

Параметр client_id из настроек сервиса HMS

---

### ИдПроекта

`Доступность: Сервер` `ТолькоЧтение`

```
ИдПроекта: Строка
```

Идентификатор проекта для HMS

---

### СекретКлиента

`Доступность: Сервер` `ТолькоЧтение`

```
СекретКлиента: Строка
```

Параметр client_secret из настроек сервиса HMS

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ДанныеАутентификацииДоставляемыхУведомлений

[ИдПриложения](../../wiki/security/deliverablenotificationauthenticationdata-ru-a04a69680ee1.md)
