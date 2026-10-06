# ПроизвольныйШаблонФормы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Forms/CustomFormTemplate_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Forms/CustomFormTemplate_ru/index.html
> SHA256: a9c24321efaf435938e3e2aef0d89f8b6a8efd9290b05f9aafe6df7a63ca446f
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::Формы::ПроизвольныйШаблонФормы` `Доступность: Клиент`

Шаблон формы, содержимое которого полностью определяется разработчиком. Не поддерживает полноценную адаптацию к мобильным устройствам.

**Сравнение**

Ссылочное

Сравнение по ссылке.

## Иерархия типа

*Базовые типы:* [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ШаблонФормы](../../wiki/interface/formtemplate-ru-27660e8ec6b4.md)

---

## Конструкторы

### ПроизвольныйШаблонФормы

`Доступность: Клиент`

```
@ИменованныеПараметры
ПроизвольныйШаблонФормы(
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
  Содержимое: Компонент?)
```

Создает объект

[ПроизвольныйШаблонФормы](../../wiki/interface/customformtemplate-ru-0778c4672078.md)

со значениями свойств, соответствующими параметрам конструктора.

---

## Свойства

### Содержимое

`Доступность: Клиент`

```
Содержимое: Компонент?
```

Произвольное содержимое формы.

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

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)
