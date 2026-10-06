# {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючОсновногоФильтра

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [exchangeplanname-dataschema-informationregistername-mainfilt-7098dc782b12-e2f49d027ce1fb04](../../raw/text-10.0/exchangeplanname-dataschema-informationregistername-mainfilt-7098dc782b12-e2f49d027ce1fb04.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ExchangePlanName.

Имена для поиска: `{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючОсновногоФильтра`, `ExchangePlanName.DataSchema.InformationRegisterName.MainFilterKey`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючОсновногоФильтра`, `DeveloperName::ProjectName::SubsystemName::ExchangePlanName.DataSchema.InformationRegisterName.MainFilterKey`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючОсновногоФильтра` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючОсновногоФильтра

`Доступность: Сервер`

```
ИмяПланаОбмена.СхемаДанных.ИмяРегистраСведений.КлючОсновногоФильтра(
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

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](exchangeplanname-dataschema-informationregistername-mainfilt-7098dc782b12.md)

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

Оригинал: [{ИмяПланаОбмена}.СхемаДанных.{ИмяРегистраСведений}.КлючОсновногоФильтра](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ExchangePlanName.DataSchema.InformationRegisterName.MainFilterKey_ru/).
