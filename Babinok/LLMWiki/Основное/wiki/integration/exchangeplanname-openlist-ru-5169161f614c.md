# {ИмяПланаОбмена}.ОткрытьСписок

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [exchangeplanname-openlist-ru-5169161f614c-51a3832e391a29bb](../../raw/text-10.0/exchangeplanname-openlist-ru-5169161f614c-51a3832e391a29bb.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ExchangePlanName.

Имена для поиска: `{ИмяПланаОбмена}.ОткрытьСписок`, `ExchangePlanName.OpenList`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.ОткрытьСписок`, `DeveloperName::ProjectName::SubsystemName::ExchangePlanName.OpenList`.

## Обзор

Команда открытия формы списка плана обмена.

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПланаОбмена}.ОткрытьСписок` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы списка плана обмена.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](../stdlib/object-ru-9e351f286699.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](../stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяПланаОбмена}.АвтоматическаяФормаСписка
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](exchangeplanname-openlist-ru-5169161f614c.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../interface/usualcommand-ru-43da648bf5af.md), [Представление](../interface/usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../interface/usualcommand-ru-43da648bf5af.md), [Представление](../interface/usualcommand-ru-43da648bf5af.md)

## See Also

- [Навигатор раздела](overview.md)
- [Элемент проекта вида «ПланОбмена» — Руководство](exchange-plan-project-element-c0fc3c4bb4ef.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [ПланОбмена — Элемент проекта](exchangeplan-47d882fe414b.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [{ИмяПланаОбмена}.ОткрытьСписок](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ExchangePlanName.OpenList_ru/).
