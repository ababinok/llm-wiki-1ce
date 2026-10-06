# ИсключениеОдновременноеИзменениеСущности

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [concurrententitymodificationexception-ru-0b6f275abc3d-3c4120c8e548bf66](../../raw/text-10.0/concurrententitymodificationexception-ru-0b6f275abc3d-3c4120c8e548bf66.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Entities.

Имена для поиска: `ИсключениеОдновременноеИзменениеСущности`, `ConcurrentEntityModificationException`, `Стд::Сущности::ИсключениеОдновременноеИзменениеСущности`, `Std::Entities::ConcurrentEntityModificationException`.

## Обзор

Исключение, выбрасываемое при попытке записи изменения/удаления одной сущности, если она уже была изменена в другом сеансе, за время редактирования.

## Документированный контракт и примеры

`Стд::Сущности::ИсключениеОдновременноеИзменениеСущности` `Доступность: Сервер`

Исключение, выбрасываемое при попытке записи изменения/удаления одной сущности, если она уже была изменена в другом сеансе, за время редактирования.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../stdlib/exception-ru-ed2632721976.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Исключение

[ВСтроку](../stdlib/exception-ru-ed2632721976.md)

[Информация](../stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../stdlib/exception-ru-ed2632721976.md), [Описание](../stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../stdlib/exception-ru-ed2632721976.md), [Причина](../stdlib/exception-ru-ed2632721976.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Сущности — Пространство имён XBSL: Std](entities-7b2acb4f9eee.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [ИсключениеОдновременноеИзменениеСущности](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/ConcurrentEntityModificationException_ru/).
