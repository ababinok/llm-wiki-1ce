# Форматируемое

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Formattable_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Formattable_ru/index.html
> SHA256: ab243e7dc6f59d7705b6e8f7c9c1d186da165d5b6d3517ab87bc8b1e4daee559
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Форматируемое` `Доступность: КлиентИСервер`

Объект, поддерживающий форматирование в строку в соответствии с определенными шаблонами.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)

*Дочерние типы:* [Время](../../wiki/stdlib/time-ru-bbaed59a0dcd.md), [Дата](../../wiki/stdlib/date-ru-d160dc00114c.md), [ДатаВремя](../../wiki/stdlib/datetime-ru-b9ec40d17fe0.md), [Длительность](../../wiki/stdlib/duration-ru-fef7ea46f329.md), [Число](../../wiki/stdlib/number-ru-dd4b54993c86.md)

---

## Методы

### Представление

`Доступность: КлиентИСервер`

```
Представление(Формат: Строка): Строка
```

Преобразует объект в строку в соответствии с указанным форматом

`Формат`

. Форматируемые типы содержат в документации описание поддерживаемых форматов.

#### Исключения

**[ИсключениеНедопустимыйФормат](../../wiki/stdlib/illegalformatexception-ru-8ff587175d1a.md)** - если указанный формат не является корректным.

**Перегрузка** [Представляемое::Представление(): Строка](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Представляемое

[Представление](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)
