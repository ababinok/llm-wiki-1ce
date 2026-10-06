# {ИмяПереключаемойКоманды}

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [switchablecommandname-ru-06c2e97ca102-fb27575dc89165a4](../../raw/text-10.0/switchablecommandname-ru-06c2e97ca102-fb27575dc89165a4.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: SwitchableCommandName.

Имена для поиска: `{ИмяПереключаемойКоманды}`, `SwitchableCommandName`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПереключаемойКоманды}`, `DeveloperName::ProjectName::SubsystemName::SwitchableCommandName`.

## Обзор

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [Одиночка](singleton-ru-cb90fb36f1e3.md), [ПереключаемаяКоманда](../interface/switchablecommand-ru-154df28f2101.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПереключаемойКоманды}` `Тип-одиночка` `Доступность: Клиент`

Переключаемая команда.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [Одиночка](singleton-ru-cb90fb36f1e3.md), [ПереключаемаяКоманда](../interface/switchablecommand-ru-154df28f2101.md)

---

## Обработчики

### Обработчик

```
Обработчик()
```

Обработчик команды. Вызывается, когда вызывается команда

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ПереключаемаяКоманда

[Активна](../interface/switchablecommand-ru-154df28f2101.md), [ИзображениеАктивного](../interface/switchablecommand-ru-154df28f2101.md), [ИзображениеНеактивного](../interface/switchablecommand-ru-154df28f2101.md), [ПредставлениеАктивного](../interface/switchablecommand-ru-154df28f2101.md), [ПредставлениеНеактивного](../interface/switchablecommand-ru-154df28f2101.md)

## Список унаследованных событий

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

## See Also

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяПереключаемойКоманды}](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SwitchableCommandName_ru/).
