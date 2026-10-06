# {ИмяПланаОбмена}.СхемаДанных.{ИмяНабораКонстант}.Запись

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [exchangeplanname-dataschema-constantssetname-record-ru-b09574b94a8c-412c0e435777d53e](../../raw/text-10.0/exchangeplanname-dataschema-constantssetname-record-ru-b09574b94a8c-412c0e435777d53e.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ExchangePlanName.

Имена для поиска: `{ИмяПланаОбмена}.СхемаДанных.{ИмяНабораКонстант}.Запись`, `ExchangePlanName.DataSchema.ConstantsSetName.Record`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяНабораКонстант}.Запись`, `DeveloperName::ProjectName::SubsystemName::ExchangePlanName.DataSchema.ConstantsSetName.Record`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Версия 9.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.СхемаДанных.{ИмяНабораКонстант}.Запись` `Доступность: Сервер`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяПланаОбмена}.СхемаДанных.{ИмяНабораКонстант}.Запись

`Доступность: Сервер`

```
ИмяПланаОбмена.СхемаДанных.ИмяНабораКонстант.Запись(
  Период: Дата,
  ConstantName: Число)
```

---

## Свойства

### ConstantName

`Доступность: Сервер`

```
ConstantName: Число
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

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](exchangeplanname-dataschema-constantssetname-record-ru-b09574b94a8c.md)

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

Оригинал: [{ИмяПланаОбмена}.СхемаДанных.{ИмяНабораКонстант}.Запись](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ExchangePlanName.DataSchema.ConstantsSetName.Record_ru/).
