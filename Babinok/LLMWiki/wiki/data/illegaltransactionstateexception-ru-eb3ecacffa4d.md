# ИсключениеНедопустимоеСостояниеТранзакции

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [illegaltransactionstateexception-ru-eb3ecacffa4d-214ae5710203a840](../../raw/text-10.0/illegaltransactionstateexception-ru-eb3ecacffa4d-214ae5710203a840.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Database.

Имена для поиска: `ИсключениеНедопустимоеСостояниеТранзакции`, `IllegalTransactionStateException`, `Стд::БазаДанных::ИсключениеНедопустимоеСостояниеТранзакции`, `Std::Database::IllegalTransactionStateException`.

## Обзор

Исключение недопустимое состояние транзакции.

## Документированный контракт и примеры

`Стд::БазаДанных::ИсключениеНедопустимоеСостояниеТранзакции` `Доступность: Сервер`

Исключение недопустимое состояние транзакции. Если транзакция находится в состоянии, при котором можно только отменить изменения транзакции (например, одна из вложенных транзакций была отменена), то при попытке фиксации изменений такой транзакции будет вызвано исключение [ИсключениеНедопустимоеСостояниеТранзакции](illegaltransactionstateexception-ru-eb3ecacffa4d.md).

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../stdlib/exception-ru-ed2632721976.md), [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИсключениеДействиеНеРазрешеноВТранзакции](actionnotallowedintransactionexception-ru-1a5984df4fee.md), [ИсключениеНетАктивнойТранзакции](noactivetransactionexception-ru-6e837ee18f97.md)

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
- [Стд::БазаДанных — Пространство имён XBSL: Std](database-c7a95b8f6198.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [ИсключениеНедопустимоеСостояниеТранзакции](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Database/IllegalTransactionStateException_ru/).
