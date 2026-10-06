# {ИмяПроцессаИнтеграции}.Схема

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationprocessname-schema-ru-1b52c9e68487-097a1c93dfb1a43b](../../raw/text-10.0/integrationprocessname-schema-ru-1b52c9e68487-097a1c93dfb1a43b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: IntegrationProcessName.

Имена для поиска: `{ИмяПроцессаИнтеграции}.Схема`, `IntegrationProcessName.Schema`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.Схема`, `DeveloperName::ProjectName::SubsystemName::IntegrationProcessName.Schema`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [СхемаПроцессаИнтеграции](integrationprocessschema-ru-4a92a86b20d0.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.Схема` `Доступность: КлиентИСервер`

Схема процесса интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [СхемаПроцессаИнтеграции](integrationprocessschema-ru-4a92a86b20d0.md)

---

## Свойства

### Узлы

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Узлы: {ИмяПроцессаИнтеграции}.УзлыСхемы
```

Узлы схемы процесса интеграции.

Переопределение: [Узлы](integrationprocessname-schema-ru-1b52c9e68487.md)

#### Примеры

Пример обработчика HTTP-запроса для программной отправки сообщения через узел типа `ПрограммныйИсточник` процесса интеграции `СетьМагазинов`.

```xbsl
метод ОтправитьСообщение(Запрос: HttpСервисЗапрос)
    знч ЯвляетсяАрхивом = Запрос.Заголовки.ПолучитьПервый("content-type") == "application/zip"
    знч Сообщение = новый СообщениеИнтеграции({"ЯвляетсяАрхивом":ЯвляетсяАрхивом}, Запрос.Тело)
    СетьМагазинов.ОтправитьСообщениеВУзлы(Сообщение, СетьМагазинов.Схема.Узлы.ОтПартнеров)
;
```

---

## Список унаследованных методов

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

### СхемаПроцессаИнтеграции

[ВСтроку](integrationprocessschema-ru-4a92a86b20d0.md)

## Список унаследованных свойств

### СхемаПроцессаИнтеграции

[Ид](integrationprocessschema-ru-4a92a86b20d0.md), [Имя](integrationprocessschema-ru-4a92a86b20d0.md)

## See Also

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяПроцессаИнтеграции}.Схема](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.Schema_ru/).
