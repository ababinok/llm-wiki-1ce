# {ИмяОбработки}.Открыть

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [processingname-open-ru-d9588a5154bc-0e6b0d08004dd7fd](../../raw/text-10.0/processingname-open-ru-d9588a5154bc-0e6b0d08004dd7fd.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ProcessingName.

Имена для поиска: `{ИмяОбработки}.Открыть`, `ProcessingName.Open`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяОбработки}.Открыть`, `DeveloperName::ProjectName::SubsystemName::ProcessingName.Open`.

## Обзор

Команда открытия формы обработки Если у обработки не указана форма, при вызове будет открыта [ИмяОбработки.АвтоматическаяФорма](../interface/processingname-automaticform-ru-40572408be14.md).

## Документированный контракт и примеры

`Версия 8.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяОбработки}.Открыть` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы обработки Если у обработки не указана форма, при вызове будет открыта [ИмяОбработки.АвтоматическаяФорма](../interface/processingname-automaticform-ru-40572408be14.md).

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](singleton-ru-cb90fb36f1e3.md)

---

## Методы

### Выполнить

`Версия 10.0 и выше`

`Доступность: Клиент`

```
Выполнить()
```

Выполняет открытие формы обработки.

---

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяОбработки}.АвтоматическаяФорма
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md) [(Переопределение)](processingname-open-ru-d9588a5154bc.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](processingname-open-ru-d9588a5154bc.md)

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

- [Навигатор раздела](../project/overview.md)
- [Элемент проекта вида «Обработка» — Руководство](../project/processing-project-element-acb124c72bfa.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [Обработка — Элемент проекта](../project/processing-3a8538244521.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяОбработки}.Открыть](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ProcessingName.Open_ru/).
