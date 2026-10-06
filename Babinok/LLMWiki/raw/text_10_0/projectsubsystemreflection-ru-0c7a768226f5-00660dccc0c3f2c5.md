# ОтражениеПодсистемыПроекта

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ProjectSubsystemReflection_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Reflection/ProjectSubsystemReflection_ru/index.html
> SHA256: ac533eabcded2487416e7f25fa65f10bd1743556dd6713e7eea97131efc7e7d7
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Отражение::ОтражениеПодсистемыПроекта` `Доступность: Сервер`

Подсистема приложения

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОтражениеПакетаПроекта](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ОтражениеПакетаПроекта

[ПоИмени](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md)

[ПоТипу](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md)

## Список унаследованных свойств

### ОтражениеПакетаПроекта

[Имя](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md), [Пакеты](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md), [ПолноеИмя](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md), [Ресурсы](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md), [Элементы](../../wiki/stdlib/projectpackagereflection-ru-906b55276dd4.md)
