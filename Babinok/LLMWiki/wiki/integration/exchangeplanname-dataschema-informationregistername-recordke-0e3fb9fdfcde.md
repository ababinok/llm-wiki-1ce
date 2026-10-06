# {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючЗаписи

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [exchangeplanname-dataschema-informationregistername-recordke-0e3fb9fdfcde-45a50984000303ac](../../raw/text-10.0/exchangeplanname-dataschema-informationregistername-recordke-0e3fb9fdfcde-45a50984000303ac.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ExchangePlanName.

Имена для поиска: `{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючЗаписи`, `ExchangePlanName.DataSchema.InformationRegisterName.RecordKey`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючЗаписи`, `DeveloperName::ProjectName::SubsystemName::ExchangePlanName.DataSchema.InformationRegisterName.RecordKey`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючЗаписи` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючЗаписи

`Доступность: Сервер`

```
ИмяПланаОбмена.СхемаДанных.ИмяРегистраСведений.КлючЗаписи(
  Период: Дата,
  ИмяИзмерения: {ИмяПланаОбмена}.СхемаДанных.{ИмяСправочника}.Ссылка?)
```

---

## Свойства

### {ИмяИзмерения}

`Доступность: Сервер`

```
ИмяИзмерения: {ИмяПланаОбмена}.СхемаДанных.{ИмяСправочника}.Ссылка?
```

---

### Период

`Доступность: Сервер`

```
Период: Дата
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

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](exchangeplanname-dataschema-informationregistername-recordke-0e3fb9fdfcde.md)

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

Оригинал: [{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючЗаписи](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ExchangePlanName.DataSchema.InformationRegisterName.RecordKey_ru/).
