# Представляемое

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [presentable-ru-fc7455a0880f-6d7775a5aa1f4829](../../raw/text-10.0/presentable-ru-fc7455a0880f-6d7775a5aa1f4829.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std.

Имена для поиска: `Представляемое`, `Presentable`, `Стд::Представляемое`, `Std::Presentable`.

## Обзор

Базовый тип объектов, имеющих удобное пользовательское представление.

## Документированный контракт и примеры

`Стд::Представляемое` `Доступность: КлиентИСервер`

Базовый тип объектов, имеющих удобное пользовательское представление.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

*Дочерние типы:* [АдресПочты](emailaddress-ru-000c5864525b.md), [Булево](boolean-ru-7823d4239bcc.md), [Версия](version-ru-29e92504e99e.md), [ИмяДокумента.Объект](../data/documentname-object-ru-55639d28c4dc.md), [ИмяИнтегрируемогоПриложения.Объект](integrableapplicationname-object-ru-2facace672c0.md), [ИмяПланаОбмена.Объект](../integration/exchangeplanname-object-ru-2882849e24b4.md), [ИмяСправочника.Объект](../data/catalogname-object-ru-8fd7b105e091.md), [ИмяХранилищаНастроек.Объект](../data/settingsstoragename-object-ru-76dd064bfbbf.md), [Локаль](locale-ru-eb59bd8c78bb.md), [Момент](instant-ru-09dd46b34eb4.md), [НавигационнаяСсылка](../interface/navigationlink-ru-ca80622e4181.md), [НедоставленноеСообщениеИнтеграции](../integration/undeliveredintegrationmessage-ru-e72b01585385.md), [Перечисление](enum-ru-a7a357b96b4c.md), [СобытиеЖурналаСобытий](eventlogevent-ru-928cb9b58d56.md), [СтандартноеХранилищеНастроек.Объект](../data/standardsettingsstorage-object-ru-cca7b461551d.md), [Строка](string-ru-1bac645acacf.md), [Сущность.Ключ](../data/entity-key-ru-7032eabc056b.md), [Сущность.Объект](../data/entity-object-ru-6a8abb73357f.md), [Тип](type-ru-d603a6747a42.md), [Ууид](uuid-ru-4831970f1083.md), [Форматируемое](formattable-ru-199658dd3e97.md)

---

## Методы

### Представление

`Доступность: КлиентИСервер`

```
Представление(): Строка
```

Возвращает пользовательское представление объекта.

**Переопределение** [Объект::Представление](object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md) [(Переопределение)](presentable-ru-fc7455a0880f.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд — Пространство имён XBSL: Std](std-c15458c2f5f0.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [Представляемое](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Presentable_ru/).
