# ДанныеАутентификацииДоставляемыхУведомлений

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [deliverablenotificationauthenticationdata-ru-a04a69680ee1-6e25d072346bef4d](../../raw/text-10.0/deliverablenotificationauthenticationdata-ru-a04a69680ee1-6e25d072346bef4d.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / DeliverableNotifications.

Имена для поиска: `ДанныеАутентификацииДоставляемыхУведомлений`, `DeliverableNotificationAuthenticationData`, `Стд::ДоставляемыеУведомления::ДанныеАутентификацииДоставляемыхУведомлений`, `Std::DeliverableNotifications::DeliverableNotificationAuthenticationData`.

## Обзор

Данные аутентификации для сервисов отправки уведомлений.

## Документированный контракт и примеры

`Стд::ДоставляемыеУведомления::ДанныеАутентификацииДоставляемыхУведомлений` `Доступность: Сервер`

Данные аутентификации для сервисов отправки уведомлений. Общий интерфейс для данных аутентификации различных сервисов

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ДанныеАутентификацииApns](apnsauthenticationdata-ru-1dbfd318b1a7.md), [ДанныеАутентификацииFcm](fcmauthenticationdata-ru-3bf1e8aa19bb.md), [ДанныеАутентификацииHms](hmsauthenticationdata-ru-c42cb4fb4e9a.md), [ДанныеАутентификацииЕдиногоМобильногоКлиента](unifiedmobileclientauthenticationdata-ru-b7c7239571e1.md), [ДанныеАутентификацииЦентраУведомлений1С](notificationcenter1cauthenticationdata-ru-6023c5c6ac77.md)

---

## Свойства

### ИдПриложения

`Доступность: Сервер` `ТолькоЧтение`

```
ИдПриложения: Строка
```

Идентификатор мобильного приложения. Идентификатор должен совпадать с полем [ИдПриложения](../stdlib/deliverablenotificationsubscriberid-ru-4e4bc11d207e.md) в объекте [ИдПодписчикаДоставляемыхУведомлений](../stdlib/deliverablenotificationsubscriberid-ru-4e4bc11d207e.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::ДоставляемыеУведомления — Пространство имён XBSL: Std](../stdlib/deliverablenotifications-6ff659677735.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [ДанныеАутентификацииДоставляемыхУведомлений](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/DeliverableNotifications/DeliverableNotificationAuthenticationData_ru/).
