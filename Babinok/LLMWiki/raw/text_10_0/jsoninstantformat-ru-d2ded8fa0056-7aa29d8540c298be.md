# ФорматМоментаJson

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Json/JsonInstantFormat_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Json/JsonInstantFormat_ru/index.html
> SHA256: 9d9cb89e39dd7798d087e3c1ea4228c74ae37d2d1869b6353a40ec7f3bac14e3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Json::ФорматМоментаJson` `Доступность: КлиентИСервер`

Форматы момента для записи JSON.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Перечисление](../../wiki/stdlib/enum-ru-a7a357b96b4c.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)

---

## Элементы

## Свойства

### Iso

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Iso
```

Формат момента ISO вида: `гггг-ММ-дд'T'ЧЧ:мм:сс.ССС'Z'`. Например: `2009-02-15T00:00:00Z`.

---

### JavaScript

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
JavaScript
```

Формат момента JavaScript вида: `1234656000000`. Указывается количество миллисекунд, прошедших с начала эры Unix (Unix Epoch), а именно `1970-01-01T00:00:00Z`.

---

### Microsoft

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Microsoft
```

Формат момента Microsoft вида: `/Date(123456000000)/`. Этот же вариант в формате JSON с экранированием будет выглядеть следующим образом: `\u002FDate(123456000000)\u002F`. Дата указывается в формате Unix-времени.

---

## Список унаследованных методов

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Перечисление

[ВСтроку](../../wiki/stdlib/enum-ru-a7a357b96b4c.md)

[Представление](../../wiki/stdlib/enum-ru-a7a357b96b4c.md)

### Представляемое

## Список унаследованных свойств

### Перечисление

[Индекс](../../wiki/stdlib/enum-ru-a7a357b96b4c.md)
