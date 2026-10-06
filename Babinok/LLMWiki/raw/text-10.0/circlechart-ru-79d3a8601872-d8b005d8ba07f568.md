# КруговаяДиаграмма

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Charts/CircleChart_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Charts/CircleChart_ru/index.html
> SHA256: 37c2220f8208f3639c3bf30e0e1010a7260ed694c1f03ba97a9e7e8124f74bb2
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Диаграммы::КруговаяДиаграмма<ТипДанных>` `Доступность: Клиент`

ТипДанных: тип данных диаграммы

Круговая диаграмма.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Диаграмма<ТипДанных>](../../wiki/interface/chart-ru-6f2fc6a259dd.md), [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [СерийнаяДиаграмма<ТипДанных, КруговаяСерияДиаграммы, ТипДанных>](../../wiki/interface/serialchart-ru-8a4e448030e5.md)

---

## Конструкторы

### КруговаяДиаграмма

`Доступность: Клиент`

```
@ИменованныеПараметры
КруговаяДиаграмма(
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
  Серии: Массив<КруговаяСерияДиаграммы>,
  Легенда: ЛегендаДиаграммы?,
  ПриНажатииНаЭлементСерии: (СерийнаяДиаграмма<ТипДанных, КруговаяСерияДиаграммы, ТипДанных>, СобытиеПриНажатииНаЭлементСерииДиаграммы<ТипДанных, КруговаяСерияДиаграммы>)->ничто,
  ПриНажатииНаЭлементЛегенды: (СерийнаяДиаграмма<ТипДанных, КруговаяСерияДиаграммы, ТипДанных>, СобытиеПриНажатииНаЭлементЛегендыДиаграммы<ТипДанных>)->ничто,
  ВнутреннийРадиус: Авто|Число)
```

Создает компонент круговой диаграммы.

---

## Свойства

### ВнутреннийРадиус

`Доступность: Клиент`

```
ВнутреннийРадиус: Авто|Число
```

Размер внутреннего радиуса круговой диаграммы в процентах от размера диаграммы. Если [Авто](../../wiki/stdlib/auto-ru-1b14ed166f8e.md), то равно 40

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

### СерийнаяДиаграмма

[Легенда](../../wiki/interface/serialchart-ru-8a4e448030e5.md), [Серии](../../wiki/interface/serialchart-ru-8a4e448030e5.md)

## Список унаследованных событий

### Диаграмма

[Источник](../../wiki/interface/chart-ru-6f2fc6a259dd.md)

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

### СерийнаяДиаграмма

[ПриНажатииНаЭлементЛегенды](../../wiki/interface/serialchart-ru-8a4e448030e5.md), [ПриНажатииНаЭлементСерии](../../wiki/interface/serialchart-ru-8a4e448030e5.md)
