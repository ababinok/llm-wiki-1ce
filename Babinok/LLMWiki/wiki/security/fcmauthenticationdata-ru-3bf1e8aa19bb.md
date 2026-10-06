# ДанныеАутентификацииFcm

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [fcmauthenticationdata-ru-3bf1e8aa19bb-47e6ff5b82e01162](../../raw/text-10.0/fcmauthenticationdata-ru-3bf1e8aa19bb-47e6ff5b82e01162.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / DeliverableNotifications.

Имена для поиска: `ДанныеАутентификацииFcm`, `FcmAuthenticationData`, `Стд::ДоставляемыеУведомления::ДанныеАутентификацииFcm`, `Std::DeliverableNotifications::FcmAuthenticationData`.

## Обзор

Данные аутентификации для сервиса FCM (Firebase Cloud Messaging)

## Документированный контракт и примеры

`Стд::ДоставляемыеУведомления::ДанныеАутентификацииFcm` `Доступность: Сервер`

Данные аутентификации для сервиса FCM (Firebase Cloud Messaging)

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ДанныеАутентификацииДоставляемыхУведомлений](deliverablenotificationauthenticationdata-ru-a04a69680ee1.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### ДанныеАутентификацииFcm

`Доступность: Сервер`

```
ДанныеАутентификацииFcm(
  ИдПриложения: Строка,
  Данные: Байты)
```

Создает объект на основании файла с настройками в формате JSON

---

## Свойства

### Данные

`Доступность: Сервер` `ТолькоЧтение`

```
Данные: Байты
```

JSON файл с параметрами доступа к сервису FCM

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

Оригинал: [ДанныеАутентификацииFcm](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/DeliverableNotifications/FcmAuthenticationData_ru/).
