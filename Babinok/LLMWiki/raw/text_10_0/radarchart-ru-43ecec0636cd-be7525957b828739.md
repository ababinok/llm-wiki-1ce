# ЛепестковаяДиаграмма

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Charts/RadarChart_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Charts/RadarChart_ru/index.html
> SHA256: 4bd02557373aff35eedcaeaecc5624069e416ba0a8f12c0a9fe97a6cfc51010e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Диаграммы::ЛепестковаяДиаграмма<ТипДанных>` `Доступность: Клиент`

Лепестковая диаграмма.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [XYДиаграмма<ТипДанных, ЛинейнаяСерияДиаграммы>](../../wiki/interface/xychart-ru-e0769f4ee02b.md), [Диаграмма<ТипДанных>](../../wiki/interface/chart-ru-6f2fc6a259dd.md), [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [СерийнаяДиаграмма<ТипДанных, SeriesType, SeriesType>](../../wiki/interface/serialchart-ru-8a4e448030e5.md)

---

## Конструкторы

### ЛепестковаяДиаграмма

`Доступность: Клиент`

```
@ИменованныеПараметры
ЛепестковаяДиаграмма(
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
  Источник: ИсточникДанныхМассив<ТипДанных>,
  Серии: Массив<ЛинейнаяСерияДиаграммы>,
  Легенда: ЛегендаДиаграммы?,
  ПриНажатииНаЭлементСерии: (СерийнаяДиаграмма<ТипДанных, ЛинейнаяСерияДиаграммы, ЛинейнаяСерияДиаграммы>, СобытиеПриНажатииНаЭлементСерииДиаграммы<ТипДанных, ЛинейнаяСерияДиаграммы>)->ничто,
  ПриНажатииНаЭлементЛегенды: (СерийнаяДиаграмма<ТипДанных, ЛинейнаяСерияДиаграммы, ЛинейнаяСерияДиаграммы>, СобытиеПриНажатииНаЭлементЛегендыДиаграммы<ЛинейнаяСерияДиаграммы>)->ничто,
  ОсиX: Массив<ОсьДиаграммы>,
  ОсиY: Массив<ОсьДиаграммы>,
  ПриНажатииНаЭлементОси: (XYДиаграмма<ТипДанных, ЛинейнаяСерияДиаграммы>, СобытиеПриНажатииНаЭлементОсиДиаграммы<ТипДанных>)->ничто)
```

Создает компонент лепестковой диаграммы.

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

### XYДиаграмма

[ОсиX](../../wiki/interface/xychart-ru-e0769f4ee02b.md), [ОсиY](../../wiki/interface/xychart-ru-e0769f4ee02b.md)

### Диаграмма

[Источник](../../wiki/interface/chart-ru-6f2fc6a259dd.md)

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

### СерийнаяДиаграмма

[Легенда](../../wiki/interface/serialchart-ru-8a4e448030e5.md), [Серии](../../wiki/interface/serialchart-ru-8a4e448030e5.md)

## Список унаследованных событий

### XYДиаграмма

[ПриНажатииНаЭлементОси](../../wiki/interface/xychart-ru-e0769f4ee02b.md)

### Диаграмма

[Источник](../../wiki/interface/chart-ru-6f2fc6a259dd.md)

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

### СерийнаяДиаграмма

[Легенда](../../wiki/interface/serialchart-ru-8a4e448030e5.md), [Серии](../../wiki/interface/serialchart-ru-8a4e448030e5.md)
