# {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.НаборЗаписей

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [exchangeplanname-dataschema-accumulationregistername-records-940ef3ca56be-06ad40db00ab1649](../../raw/text-10.0/exchangeplanname-dataschema-accumulationregistername-records-940ef3ca56be-06ad40db00ab1649.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ExchangePlanName.

Имена для поиска: `{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.НаборЗаписей`, `ExchangePlanName.DataSchema.AccumulationRegisterName.RecordSet`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.НаборЗаписей`, `DeveloperName::ProjectName::SubsystemName::ExchangePlanName.DataSchema.AccumulationRegisterName.RecordSet`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.НаборЗаписей` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.НаборЗаписей

`Доступность: Сервер`

```
ИмяПланаОбмена.СхемаДанных.ИмяРегистраНакопления.НаборЗаписей(
  Filter: {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.КлючОсновногоФильтра,
  Records: Массив<{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.Запись>)
```

---

## Свойства

### Filter

`Доступность: Сервер`

```
Filter: {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.КлючОсновногоФильтра
```

---

### Records

`Доступность: Сервер`

```
Records: Массив<{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.Запись>
```

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](exchangeplanname-dataschema-accumulationregistername-records-940ef3ca56be.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Элемент проекта вида «ПланОбмена» — Руководство](exchange-plan-project-element-c0fc3c4bb4ef.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [ПланОбмена — Элемент проекта](exchangeplan-47d882fe414b.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраНакопления}.НаборЗаписей](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ExchangePlanName.DataSchema.AccumulationRegisterName.RecordSet_ru/).
