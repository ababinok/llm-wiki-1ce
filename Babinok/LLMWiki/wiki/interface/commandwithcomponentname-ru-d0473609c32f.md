# {ИмяКомандыСКомпонентом}

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [commandwithcomponentname-ru-d0473609c32f-220fce3cdb1ab8e5](../../raw/text-10.0/commandwithcomponentname-ru-d0473609c32f-220fce3cdb1ab8e5.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: CommandWithComponentName.

Имена для поиска: `{ИмяКомандыСКомпонентом}`, `CommandWithComponentName`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяКомандыСКомпонентом}`, `DeveloperName::ProjectName::SubsystemName::CommandWithComponentName`.

## Обзор

*Базовые типы:* [Команда](command-ru-ad3bc8ea1407.md), [КомандаСКомпонентом<Компонент>](commandwithcomponent-ru-4b1e72350e5a.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](usualcommand-ru-43da648bf5af.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяКомандыСКомпонентом}` `Доступность: Клиент`

Команда с компонентом

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](command-ru-ad3bc8ea1407.md), [КомандаСКомпонентом<Компонент>](commandwithcomponent-ru-4b1e72350e5a.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](usualcommand-ru-43da648bf5af.md)

---

## Конструкторы

### {ИмяКомандыСКомпонентом}

`Доступность: Клиент`

```
ИмяКомандыСКомпонентом(Компонент: Компонент)
```

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

[Выполнить](command-ru-ad3bc8ea1407.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](command-ru-ad3bc8ea1407.md), [Видимость](command-ru-ad3bc8ea1407.md), [Доступность](command-ru-ad3bc8ea1407.md), [ОпасностьДействия](command-ru-ad3bc8ea1407.md)

### КомандаСКомпонентом

[Компонент](commandwithcomponent-ru-4b1e72350e5a.md)

### ОбычнаяКоманда

[Изображение](usualcommand-ru-43da648bf5af.md), [Представление](usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](command-ru-ad3bc8ea1407.md), [Видимость](command-ru-ad3bc8ea1407.md), [Доступность](command-ru-ad3bc8ea1407.md), [ОпасностьДействия](command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](usualcommand-ru-43da648bf5af.md), [Представление](usualcommand-ru-43da648bf5af.md)

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [КомандаСКомпонентом — Элемент проекта](commandwithcomponent-ru-bd6661ad8549.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [{ИмяКомандыСКомпонентом}](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/CommandWithComponentName_ru/).
