# ГрафическаяСхема

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/GraphicalSchemas/GraphicalSchema_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/GraphicalSchemas/GraphicalSchema_ru/index.html
> SHA256: ed32fb083fde6f586250001c88f4e051b518746d516278d9888bd0a307289490
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ГрафическиеСхемы::ГрафическаяСхема` `Доступность: Клиент`

Базовый компонент для графических схем.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ДревовиднаяСхема](../../wiki/interface/treeschema-ru-44f073705d32.md)

---

## Свойства

### Отдалить

`Доступность: Клиент` `ТолькоЧтение`

```
Отдалить: Команда
```

Системная команда, уменьшающая масштаб отображения.

---

### ПодогнатьКОбластиПросмотра

`Доступность: Клиент` `ТолькоЧтение`

```
ПодогнатьКОбластиПросмотра: Команда
```

Системная команда, устанавливающая масштаб, позволяющий разместить все содержимое графической схемы.

---

### Приблизить

`Доступность: Клиент` `ТолькоЧтение`

```
Приблизить: Команда
```

Системная команда, увеличивающая масштаб отображения.

---

### СброситьМасштабирование

`Доступность: Клиент` `ТолькоЧтение`

```
СброситьМасштабирование: Команда
```

Системная команда, сбрасывающая масштаб графической схемы в 1 к 1.

---

## Методы

### ПодогнатьКОбластиПросмотра

`Доступность: Клиент`

```
ПодогнатьКОбластиПросмотра()
```

Масштабирует и центрирует схему так, что бы она вмещалась целиком в область просмотра.

---

### ЦентрироватьПоЭлементу

`Доступность: Клиент`

```
ЦентрироватьПоЭлементу(
  Элемент: ЭлементГрафическойСхемы,
  СброситьМасштабирование: Булево = Ложь)
```

Центрирует и масштабирует область просмотра на указанном элементе. Если параметр

`СброситьМасштабирование`

равен

`Истина`

, то масштабирование будет сброшено в 1 к 1.

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
