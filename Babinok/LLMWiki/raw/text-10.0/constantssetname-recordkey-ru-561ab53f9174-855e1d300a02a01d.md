# {ИмяНабораКонстант}.КлючЗаписи

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ConstantsSetName.RecordKey_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ConstantsSetName.RecordKey_ru/index.html
> SHA256: 7fb6663d0d64b7a089df58a0e5dfd6448cdad19df6ab7c187333d73347066699
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 9.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяНабораКонстант}.КлючЗаписи` `Доступность: КлиентИСервер`

Содержит значения ключ записи набора констант.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [НаборКонстант.КлючЗаписи](../../wiki/stdlib/constantsset-recordkey-ru-a342a124c6a2.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [Сущность.Ключ](../../wiki/data/entity-key-ru-7032eabc056b.md)

---

## Примеры

**Общие примеры**

```xbsl
знч КлючЗаписи = новый КурсыВалют.КлючЗаписи(Период = Дата{2025-03-25})
```

---

## Конструкторы

### {ИмяНабораКонстант}.КлючЗаписи

`Доступность: КлиентИСервер`

```
@ИменованныеПараметры
ИмяНабораКонстант.КлючЗаписи(Период: Дата)
```

---

## Свойства

### Период

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Период: Дата
```

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

### Представление

`Доступность: КлиентИСервер`

```
Представление(): Строка
```

**Переопределение** [Представляемое::Представление](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/stdlib/constantssetname-recordkey-ru-561ab53f9174.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Представляемое

[Представление](../../wiki/stdlib/presentable-ru-fc7455a0880f.md) [(Переопределение)](../../wiki/stdlib/constantssetname-recordkey-ru-561ab53f9174.md)
