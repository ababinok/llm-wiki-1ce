# {ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.Компоненты

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrableapplicationname-automaticlistform-components-ru-1725f0e28789-2a7070c0a06c9267](../../raw/text-10.0/integrableapplicationname-automaticlistform-components-ru-1725f0e28789-2a7070c0a06c9267.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: IntegrableApplicationName.

Имена для поиска: `{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.Компоненты`, `IntegrableApplicationName.AutomaticListForm.Components`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.Компоненты`, `DeveloperName::ProjectName::SubsystemName::IntegrableApplicationName.AutomaticListForm.Components`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.Компоненты` `Доступность: Клиент`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Свойства

### DirectConnectionSettings_Address

`Доступность: Клиент` `ТолькоЧтение`

```
DirectConnectionSettings_Address: СтандартнаяКолонкаТаблицы<СтрокаДинамическогоСписка<{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка>>
```

---

### DirectConnectionSettings_ClientId

`Доступность: Клиент` `ТолькоЧтение`

```
DirectConnectionSettings_ClientId: СтандартнаяКолонкаТаблицы<СтрокаДинамическогоСписка<{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка>>
```

---

### DirectConnectionSettings_ClientSecret

`Доступность: Клиент` `ТолькоЧтение`

```
DirectConnectionSettings_ClientSecret: СтандартнаяКолонкаТаблицы<СтрокаДинамическогоСписка<{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка>>
```

---

### ОсновнаяТаблица

`Доступность: Клиент` `ТолькоЧтение`

```
ОсновнаяТаблица: Таблица<ДинамическийСписок<{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка>>
```

---

## Методы

### Получить

`Доступность: Клиент`

```
Получить(Ключ: неизвестно): неизвестно
```

---

### СодержитКлюч

`Доступность: Клиент`

```
СодержитКлюч(Ключ: неизвестно): Булево
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Элемент проекта вида «ИнтегрируемоеПриложение» — Руководство](../project/integrable-application-project-element-9568214a365e.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [ИнтегрируемоеПриложение — Элемент проекта](../project/integrableapplication-6b34fc19cb72.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [{ИмяИнтегрируемогоПриложения}.АвтоматическаяФормаСписка.Компоненты](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrableApplicationName.AutomaticListForm.Components_ru/).
