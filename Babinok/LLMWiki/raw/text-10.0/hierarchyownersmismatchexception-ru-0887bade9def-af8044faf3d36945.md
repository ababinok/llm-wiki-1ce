# ИсключениеНесоответствияВладельцевИерархии

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/Hierarchy/HierarchyOwnersMismatchException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Entities/Hierarchy/HierarchyOwnersMismatchException_ru/index.html
> SHA256: 5a743c764eeebf1dc11fd1bde181fcc8242c362d084d8e0ae12fd30592463d9e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Сущности::Иерархия::ИсключениеНесоответствияВладельцевИерархии` `Доступность: Сервер`

Исключение выбрасывается при попытке записи элемента, чей владелец отличается от владельца родительского элемента в иерархии.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

```xbsl
метод НесоответствиеВладельцев(Объект: Подразделения.Объект)
    попытка
        Объект.Записать()
    поймать Исключение: ИсключениеНесоответствияВладельцевИерархии
        // Обработка ошибки несоответствия владельцев
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
