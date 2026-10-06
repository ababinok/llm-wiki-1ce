# ИсключениеЦиклВИерархии

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/Hierarchy/CycleInHierarchyException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Entities/Hierarchy/CycleInHierarchyException_ru/index.html
> SHA256: d2ed2bc2e4c5e2372f154fa9d27388629fc728489242b2d59d989bd358ee99a3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Сущности::Иерархия::ИсключениеЦиклВИерархии` `Доступность: Сервер`

Исключение выбрасывается при попытке записи элемента, который образует цикл в иерархии.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ЦиклВИерархии(ПодразделениеСсылка: Подразделения.Ссылка)
    попытка
        знч ПодразделениеОбъект = ПодразделениеСсылка.ЗагрузитьОбъект()
        ПодразделениеОбъект.Родитель = ПодразделениеСсылка
        ПодразделениеОбъект.Записать()
    поймать Исключение: ИсключениеЦиклВИерархии
        // Обработка ошибки образования цикла
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
