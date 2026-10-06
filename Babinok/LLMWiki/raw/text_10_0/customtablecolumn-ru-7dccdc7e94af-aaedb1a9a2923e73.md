# ПроизвольнаяКолонкаТаблицы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Lists/CustomTableColumn_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Lists/CustomTableColumn_ru/index.html
> SHA256: 457152c1c201440d7db2c0ea8836e6efde0449da22642d9074bd2736126c193d
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Списки::ПроизвольнаяКолонкаТаблицы<ТипДанных>` `Доступность: Клиент`

ТипДанных: тип данных колонки таблицы

Описывает колонку таблицы с произвольным содержимым.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [КолонкаТаблицы<ТипДанных>](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### ПроизвольнаяКолонкаТаблицы

`Доступность: Клиент`

```
@ИменованныеПараметры
ПроизвольнаяКолонкаТаблицы(
  Видимость: Авто|Булево,
  Доступность: Авто|Булево,
  ТолькоЧтение: Авто|Булево,
  ВыравниваниеВГруппеПоВертикали: Авто|ВыравниваниеПоВертикали,
  ВыравниваниеВГруппеПоГоризонтали: Авто|ВыравниваниеПоГоризонтали,
  ВесПриРастягивании: Авто|Число,
  Высота: Авто|Число,
  Ширина: Авто|Число,
  ШиринаВКолонках: Авто|ШиринаВКолонках,
  МаксимальнаяВысота: Авто|Число,
  МаксимальнаяШирина: Авто|Число,
  МинимальнаяВысота: Авто|Число,
  МинимальнаяШирина: Авто|Число,
  РастягиватьПоВертикали: Авто|Булево,
  РастягиватьПоГоризонтали: Авто|Булево,
  ПриПеретаскивании: (Компонент, СобытиеПриПеретаскивании)->ничто,
  ПриНаведении: (Компонент, СобытиеКомпонента)->ничто,
  ПриПотереНаведения: (Компонент, СобытиеКомпонента)->ничто,
  Заголовок: Строка,
  ПолеЗначения: Строка,
  Важность: ВажностьКомпонента,
  РазрешитьСжатие: Авто|Булево,
  ОтключитьСортировку: Булево,
  ДанныеСтроки: ТипДанных,
  ОтображатьЗаголовокВКарточке: Булево,
  НастройкиРедактирования: НастройкиРедактированияПоляВвода|НастройкиРедактированияПереключателя|?,
  Содержимое: Компонент?)
```

Создает компонент со значениями свойств, соответствующими параметрам конструктора.

---

## Свойства

### Содержимое

`Доступность: Клиент`

```
Содержимое: Компонент?
```

Определяет содержимое ячейки данной колонки. Свойство недоступно из прикладного языка. Должно быть заполнено при описании колонки в таблице.

---

## Список унаследованных методов

### Компонент

[Активировать](../../wiki/interface/component-ru-bad1c84be995.md)

[ОтключитьОбработчикТаймера](../../wiki/interface/component-ru-bad1c84be995.md)

[ПодключитьОбработчикТаймера](../../wiki/interface/component-ru-bad1c84be995.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### КолонкаТаблицы

[Важность](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [ДанныеСтроки](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [Заголовок](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [НастройкиРедактирования](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [ОтключитьСортировку](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [ОтображатьЗаголовокВКарточке](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [ПолеЗначения](../../wiki/interface/tablecolumn-ru-90496d65cde5.md), [РазрешитьСжатие](../../wiki/interface/tablecolumn-ru-90496d65cde5.md)

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

## Список унаследованных событий

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)
