# СобытиеПревышенияЗапросомОграничения

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [requestlimitexceededevent-ru-46f0b65bfdda-2ea443d33c95389b](../../raw/text-10.0/requestlimitexceededevent-ru-46f0b65bfdda-2ea443d33c95389b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Events.

Имена для поиска: `СобытиеПревышенияЗапросомОграничения`, `RequestLimitExceededEvent`, `Стд::События::СобытиеПревышенияЗапросомОграничения`, `Std::Events::RequestLimitExceededEvent`.

## Обзор

Событие генерируется при превышении запросом хотя бы одного из ограничений, установленных для приложения

## Документированный контракт и примеры

`Стд::События::СобытиеПревышенияЗапросомОграничения` `Доступность: Сервер`

Событие генерируется при превышении запросом хотя бы одного из ограничений, установленных для приложения

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### ВидПревышенногоОграничения

`Доступность: Сервер` `ТолькоЧтение`

```
ВидПревышенногоОграничения: Строка?
```

Вид ограничения, превышенного запросом

---

### ЗначениеПревышенногоОграничения

`Доступность: Сервер` `ТолькоЧтение`

```
ЗначениеПревышенногоОграничения: Число?
```

Значение ограничения, превышенного запросом

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

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::События — Пространство имён XBSL: Std](../stdlib/events-97e652bcee43.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [СобытиеПревышенияЗапросомОграничения](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Events/RequestLimitExceededEvent_ru/).
