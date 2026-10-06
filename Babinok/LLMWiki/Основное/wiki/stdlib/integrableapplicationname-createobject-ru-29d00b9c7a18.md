# {ИмяИнтегрируемогоПриложения}.СоздатьОбъект

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrableapplicationname-createobject-ru-29d00b9c7a18-73e8a1b337653981](../../raw/text_10_0/integrableapplicationname-createobject-ru-29d00b9c7a18-73e8a1b337653981.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: IntegrableApplicationName.

Имена для поиска: `{ИмяИнтегрируемогоПриложения}.СоздатьОбъект`, `IntegrableApplicationName.CreateObject`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяИнтегрируемогоПриложения}.СоздатьОбъект`, `DeveloperName::ProjectName::SubsystemName::IntegrableApplicationName.CreateObject`.

## Обзор

Команда открытия формы нового объекта интегрируемого приложения.

## Документированный контракт и примеры

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяИнтегрируемогоПриложения}.СоздатьОбъект` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы нового объекта интегрируемого приложения.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаОбъекта
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](integrableapplicationname-createobject-ru-29d00b9c7a18.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

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

- [Навигатор раздела](../integration/overview.md)
- [Элемент проекта вида «ИнтегрируемоеПриложение» — Руководство](../project/integrable-application-project-element-9568214a365e.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [ИнтегрируемоеПриложение — Элемент проекта](../project/integrableapplication-6b34fc19cb72.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [{ИмяИнтегрируемогоПриложения}.СоздатьОбъект](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrableApplicationName.CreateObject_ru/).
