# ОтражениеПодсистемыПроекта

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [projectsubsystemreflection-ru-0c7a768226f5-00660dccc0c3f2c5](../../raw/text-10.0/projectsubsystemreflection-ru-0c7a768226f5-00660dccc0c3f2c5.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Reflection.

Имена для поиска: `ОтражениеПодсистемыПроекта`, `ProjectSubsystemReflection`, `Стд::Отражение::ОтражениеПодсистемыПроекта`, `Std::Reflection::ProjectSubsystemReflection`.

## Обзор

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ОтражениеПакетаПроекта](projectpackagereflection-ru-906b55276dd4.md)

## Документированный контракт и примеры

`Стд::Отражение::ОтражениеПодсистемыПроекта` `Доступность: Сервер`

Подсистема приложения

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ОтражениеПакетаПроекта](projectpackagereflection-ru-906b55276dd4.md)

---

## Свойства

### Представление

`Доступность: Сервер` `ТолькоЧтение`

```
Представление: Строка
```

Интерфейсное представление подсистемы

---

## Методы

### ПолучитьВсе

`Доступность: Сервер` `Статический`

```
ПолучитьВсе(): ЧитаемаяКоллекция<ОтражениеПодсистемыПроекта>
```

Статический метод. Позволяет получить все подсистемы всех проектов (приложения и всех библиотек).

#### Примеры

```xbsl
знч ВсеПодсистемы = ОтражениеПодсистемыПроекта.ПолучитьВсе()
```

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

### ОтражениеПакетаПроекта

[ПоИмени](projectpackagereflection-ru-906b55276dd4.md)

[ПоТипу](projectpackagereflection-ru-906b55276dd4.md)

## Список унаследованных свойств

### ОтражениеПакетаПроекта

[Имя](projectpackagereflection-ru-906b55276dd4.md), [Пакеты](projectpackagereflection-ru-906b55276dd4.md), [ПолноеИмя](projectpackagereflection-ru-906b55276dd4.md), [Ресурсы](projectpackagereflection-ru-906b55276dd4.md), [Элементы](projectpackagereflection-ru-906b55276dd4.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Отражение — Пространство имён XBSL: Std](reflection-9e3e27bfa992.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ОтражениеПодсистемыПроекта](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ProjectSubsystemReflection_ru/).
