# {ИмяПроцессаИнтеграции}.Схема

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.Schema_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.Schema_ru/index.html
> SHA256: 55586076971e11cf9d75d1d9a544989c96d3db4b23276a4e90430f4d6041fa0f
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.Схема` `Доступность: КлиентИСервер`

Схема процесса интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [СхемаПроцессаИнтеграции](../../wiki/integration/integrationprocessschema-ru-4a92a86b20d0.md)

---

## Свойства

### Узлы

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Узлы: {ИмяПроцессаИнтеграции}.УзлыСхемы
```

Узлы схемы процесса интеграции.

Переопределение: [Узлы](../../wiki/integration/integrationprocessname-schema-ru-1b52c9e68487.md)

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

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### СхемаПроцессаИнтеграции

[ВСтроку](../../wiki/integration/integrationprocessschema-ru-4a92a86b20d0.md)

## Список унаследованных свойств

### СхемаПроцессаИнтеграции

[Ид](../../wiki/integration/integrationprocessschema-ru-4a92a86b20d0.md), [Имя](../../wiki/integration/integrationprocessschema-ru-4a92a86b20d0.md)
