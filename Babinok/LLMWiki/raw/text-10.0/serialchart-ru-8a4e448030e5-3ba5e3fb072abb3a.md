# СерийнаяДиаграмма

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Charts/SerialChart_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Charts/SerialChart_ru/index.html
> SHA256: 3acbddfa31e37efff0e13c5f1fe27e7ceb74d5b9d49b73e09af15dca235307d6
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Диаграммы::СерийнаяДиаграмма<ТипДанных,ТипСерии,ТипЭлементаЛегенды>` `Доступность: Клиент`

Базовый компонент диаграмм с сериями.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Диаграмма<ТипДанных>](../../wiki/interface/chart-ru-6f2fc6a259dd.md), [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [XYДиаграмма](../../wiki/interface/xychart-ru-e0769f4ee02b.md), [ВоронкообразнаяДиаграмма](../../wiki/interface/funnelchart-ru-70e3fce7f964.md), [ДиаграммаСпидометр](../../wiki/interface/speedometerchart-ru-356eedd65c4c.md), [КруговаяДиаграмма](../../wiki/interface/circlechart-ru-79d3a8601872.md)

---

## Свойства

### Легенда

`Доступность: Клиент`

```
Легенда: ЛегендаДиаграммы?
```

Описание легенды диаграммы.

---

### Серии

`Доступность: Клиент`

```
Серии: Массив<ТипСерии>
```

Коллекция серий диаграммы.

---

## События

### ПриНажатииНаЭлементЛегенды

`Доступность: Клиент`

```
ПриНажатииНаЭлементЛегенды: (
  СерийнаяДиаграмма<ТипДанных, ТипСерии, ТипЭлементаЛегенды>,
  СобытиеПриНажатииНаЭлементЛегендыДиаграммы<ТипЭлементаЛегенды>)->ничто
```

Вызывается при нажатии на элемент легенды.

---

### ПриНажатииНаЭлементСерии

`Доступность: Клиент`

```
ПриНажатииНаЭлементСерии: (
  СерийнаяДиаграмма<ТипДанных, ТипСерии, ТипЭлементаЛегенды>,
  СобытиеПриНажатииНаЭлементСерииДиаграммы<ТипДанных, ТипСерии>)->ничто
```

Вызывается при нажатии на элемент серии.

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

### Диаграмма

[Источник](../../wiki/interface/chart-ru-6f2fc6a259dd.md)

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

## Список унаследованных событий

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)
