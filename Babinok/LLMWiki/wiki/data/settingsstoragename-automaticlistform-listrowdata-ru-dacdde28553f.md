# {ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [settingsstoragename-automaticlistform-listrowdata-ru-dacdde28553f-2fd8dfd15d7c1ff6](../../raw/text-10.0/settingsstoragename-automaticlistform-listrowdata-ru-dacdde28553f-2fd8dfd15d7c1ff6.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: SettingsStorageName.

Имена для поиска: `{ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка`, `SettingsStorageName.AutomaticListForm.ListRowData`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка`, `DeveloperName::ProjectName::SubsystemName::SettingsStorageName.AutomaticListForm.ListRowData`.

## Обзор

*Базовые типы:* [ДанныеСтрокиДинамическогоСписка<Объект>](../interface/dynamiclistrowdata-ru-944b789a8d8c.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка` `Доступность: Клиент`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ДанныеСтрокиДинамическогоСписка<Объект>](../interface/dynamiclistrowdata-ru-944b789a8d8c.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка

`Доступность: Клиент`

```
ИмяХранилищаНастроек.АвтоматическаяФормаСписка.ДанныеСтрокиСписка(
  Variant: Булево,
  User: Пользователи.Ссылка?,
  Value: Строка,
  ObjectKey: Строка,
  SettingKey: Строка,
  Shared: Булево,
  Name: Строка)
```

---

## Свойства

### Name

`Доступность: Клиент` `ТолькоЧтение`

```
Name: Строка
```

---

### ObjectKey

`Доступность: Клиент` `ТолькоЧтение`

```
ObjectKey: Строка
```

---

### SettingKey

`Доступность: Клиент` `ТолькоЧтение`

```
SettingKey: Строка
```

---

### Shared

`Доступность: Клиент` `ТолькоЧтение`

```
Shared: Булево
```

---

### User

`Доступность: Клиент` `ТолькоЧтение`

```
User: Пользователи.Ссылка?
```

---

### Value

`Доступность: Клиент` `ТолькоЧтение`

```
Value: Строка
```

---

### Variant

`Доступность: Клиент` `ТолькоЧтение`

```
Variant: Булево
```

---

## Методы

### ВСтроку

`Доступность: Клиент`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](settingsstoragename-automaticlistform-listrowdata-ru-dacdde28553f.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [ХранилищеНастроек — Элемент проекта](settingsstorage-c57f34254260.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [{ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.ДанныеСтрокиСписка](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SettingsStorageName.AutomaticListForm.ListRowData_ru/).
