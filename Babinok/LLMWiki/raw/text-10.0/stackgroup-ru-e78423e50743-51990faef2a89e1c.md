# СтековаяГруппа

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Groups/StackGroup_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Groups/StackGroup_ru/index.html
> SHA256: f7e0e3265426a32a1813bfd171538a591f355e67aa7bcde0bb7e6360fbfb98a6
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Группы::СтековаяГруппа` `Доступность: Клиент`

Группа, отображающая компоненты один над другим. Видимым является только последний из них.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### СтековаяГруппа

`Доступность: Клиент`

```
@ИменованныеПараметры
СтековаяГруппа(
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
  Содержимое: Массив<Компонент>)
```

Создает компонент со значениями свойств, соответствующими параметрам конструктора.

---

## Свойства

### Содержимое

`Доступность: Клиент`

```
Содержимое: Массив<Компонент>
```

Массив компонентов стековой группы.

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

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

## Список унаследованных событий

### Компонент

[ПриНаведении](../../wiki/interface/component-ru-bad1c84be995.md), [ПриПеретаскивании](../../wiki/interface/component-ru-bad1c84be995.md), [ПриПотереНаведения](../../wiki/interface/component-ru-bad1c84be995.md)
