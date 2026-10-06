# ИсключениеЗаписьНеУникальна

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/RecordNotUniqueException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Entities/RecordNotUniqueException_ru/index.html
> SHA256: 13888b97fec71261a9967bf5cf7c0598ead25322df21f3c82dacdb289f258f3c
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Сущности::ИсключениеЗаписьНеУникальна` `Доступность: Сервер`

Исключение выбрасывается при обнаружении нарушения уникальности ключевых полей записи.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ПримерИсключениеЗаписьНеУникальна(НаборЗаписей: КурсыВалют.НаборЗаписей)
    попытка
        НаборЗаписей.Записать()
    поймать Исключение: ИсключениеЗаписьНеУникальна
        // Обработка ошибки не уникальности записей
    ;
;
```

---

## Список унаследованных методов

### Исключение

[ВСтроку](../../wiki/stdlib/exception-ru-ed2632721976.md)

[Информация](../../wiki/stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../../wiki/stdlib/exception-ru-ed2632721976.md), [Описание](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../../wiki/stdlib/exception-ru-ed2632721976.md), [Причина](../../wiki/stdlib/exception-ru-ed2632721976.md)
