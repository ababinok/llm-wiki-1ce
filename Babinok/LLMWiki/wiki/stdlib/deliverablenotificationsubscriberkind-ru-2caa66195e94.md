# ВидПодписчикаДоставляемыхУведомлений

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [deliverablenotificationsubscriberkind-ru-2caa66195e94-e97dee8f5be05cd5](../../raw/text-10.0/deliverablenotificationsubscriberkind-ru-2caa66195e94-e97dee8f5be05cd5.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / DeliverableNotifications.

Имена для поиска: `ВидПодписчикаДоставляемыхУведомлений`, `DeliverableNotificationSubscriberKind`, `Стд::ДоставляемыеУведомления::ВидПодписчикаДоставляемыхУведомлений`, `Std::DeliverableNotifications::DeliverableNotificationSubscriberKind`.

## Обзор

Вид службы, используемый для доставки push-уведомлений.

## Документированный контракт и примеры

`Стд::ДоставляемыеУведомления::ВидПодписчикаДоставляемыхУведомлений` `Доступность: КлиентИСервер`

Вид службы, используемый для доставки push-уведомлений.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [Перечисление](enum-ru-a7a357b96b4c.md), [Представляемое](presentable-ru-fc7455a0880f.md)

---

## Элементы

## Свойства

### Apns

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Apns
```

Apple Push Notification Service. Сервис, используемый для доставки push-уведомлений на устройства под управлением iOS.

---

### Fcm

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Fcm
```

Firebase Cloud Messaging. Сервис, используемый для доставки push-уведомлений на устройства под управлением ОС Android через сервисы Google.

---

### Hms

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Hms
```

Huawei Mobile Services. Сервис, используемый для доставки push-уведомлений на устройства под управлением ОС Android через сервисы Huawei.

---

## Список унаследованных методов

### Объект

[ПолучитьТип](object-ru-9e351f286699.md)

### Перечисление

[ВСтроку](enum-ru-a7a357b96b4c.md)

[Представление](enum-ru-a7a357b96b4c.md)

### Представляемое

## Список унаследованных свойств

### Перечисление

[Индекс](enum-ru-a7a357b96b4c.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::ДоставляемыеУведомления — Пространство имён XBSL: Std](deliverablenotifications-6ff659677735.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ВидПодписчикаДоставляемыхУведомлений](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/DeliverableNotifications/DeliverableNotificationSubscriberKind_ru/).
