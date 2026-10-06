# ИсключениеНедопустимоеСостояниеТранзакции

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Database/IllegalTransactionStateException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Database/IllegalTransactionStateException_ru/index.html
> SHA256: 8f7608ba8010d29458523ec926b943bbb4cec7daf19dbd164f38975d852586a7
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::БазаДанных::ИсключениеНедопустимоеСостояниеТранзакции` `Доступность: Сервер`

Исключение недопустимое состояние транзакции. Если транзакция находится в состоянии, при котором можно только отменить изменения транзакции (например, одна из вложенных транзакций была отменена), то при попытке фиксации изменений такой транзакции будет вызвано исключение [ИсключениеНедопустимоеСостояниеТранзакции](../../wiki/data/illegaltransactionstateexception-ru-eb3ecacffa4d.md).

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИсключениеДействиеНеРазрешеноВТранзакции](../../wiki/data/actionnotallowedintransactionexception-ru-1a5984df4fee.md), [ИсключениеНетАктивнойТранзакции](../../wiki/data/noactivetransactionexception-ru-6e837ee18f97.md)

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
