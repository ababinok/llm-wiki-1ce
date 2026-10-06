# СобытиеОткатТранзакции

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [transactionrollbackevent-ru-4b815f2b556e-d1126f7b14c48d68](../../raw/text-10.0/transactionrollbackevent-ru-4b815f2b556e-d1126f7b14c48d68.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Database / Events.

Имена для поиска: `СобытиеОткатТранзакции`, `TransactionRollbackEvent`, `Стд::БазаДанных::События::СобытиеОткатТранзакции`, `Std::Database::Events::TransactionRollbackEvent`.

## Обзор

Событие записывается при неудачном завершении и откате транзакции.

## Документированный контракт и примеры

`Стд::БазаДанных::События::СобытиеОткатТранзакции` `Доступность: Сервер`

Событие записывается при неудачном завершении и откате транзакции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### ИдТранзакции

`Доступность: Сервер` `ТолькоЧтение`

```
ИдТранзакции: Строка?
```

Идентификатор отслеживаемой транзакции.

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

### Представляемое

### СобытиеЖурналаСобытий

[ПолучитьСвойство](../stdlib/eventlogevent-ru-928cb9b58d56.md)

[Представление](../stdlib/eventlogevent-ru-928cb9b58d56.md)

## Список унаследованных свойств

### СобытиеЖурналаСобытий

[Важность](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ВидСобытия](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Длительность](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Ид](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ИдОшибки](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Имя](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ИнформацияОВнутреннемИсключении](../stdlib/eventlogevent-ru-928cb9b58d56.md), [КонецОперации](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Момент](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Операции](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Описание](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ОписанияСвойств](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Родитель](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Свойства](../stdlib/eventlogevent-ru-928cb9b58d56.md), [Успешно](../stdlib/eventlogevent-ru-928cb9b58d56.md), [ХарактерОшибки](../stdlib/eventlogevent-ru-928cb9b58d56.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::БазаДанных::События — Пространство имён XBSL: Std / Database](events-0298a3a54425.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [СобытиеОткатТранзакции](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Database/Events/TransactionRollbackEvent_ru/).
