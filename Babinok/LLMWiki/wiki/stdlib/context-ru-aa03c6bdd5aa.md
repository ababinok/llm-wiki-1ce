# Контекст

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [context-ru-aa03c6bdd5aa-2e4e41df6fad098b](../../raw/text-10.0/context-ru-aa03c6bdd5aa-2e4e41df6fad098b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std.

Имена для поиска: `Контекст`, `Context`, `Стд::Контекст`, `Std::Context`.

## Обзор

Базовый тип объектов, неявно меняющих поведение системы.

## Документированный контракт и примеры

`Стд::Контекст` `Доступность: КлиентИСервер`

Базовый тип объектов, неявно меняющих поведение системы. Обязательно должен использоваться в исп-выражении или исп-переменной при возврате из метода или создании конструктором. Таким образом, областью действия контекста является область видимости.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Закрываемое](closeable-ru-67cd73fca69d.md), [Объект](object-ru-9e351f286699.md)

*Дочерние типы:* [ГрупповаяОперация](batchoperation-ru-5cb1faf5ae53.md), [КонтекстБлокировкиЗасыпания](../interface/sleeplockcontext-ru-3eb8360b8ce3.md), [КонтекстДоступа](accesscontext-ru-aeec85a9e774.md), [КонтекстЛокализации](localizationcontext-ru-9813c22da69d.md), [КонтекстОперацииЖурналаСобытий](eventlogoperationcontext-ru-6654ff718ec1.md), [КонтекстПользователяВзаимодействия](../integration/collaborationusercontext-ru-7578c2bba74c.md), [ОбластьВидимостиВременныхТаблиц](../data/temptablesvisibilityscope-ru-54872f64dd09.md), [ОбработкаВходящегоСообщенияОбмена](../integration/processingincomingexchangemessage-ru-f5cc1468fcea.md), [ОбработкаИсходящегоСообщенияОбмена](../integration/processingoutgoingexchangemessage-ru-c9121ce320e2.md), [ТранзакцияSql](../data/sqltransaction-ru-1145231f0cfe.md), [Транзакция](../data/transaction-ru-b357c9a8248c.md)

---

## Список унаследованных методов

### Закрываемое

[Закрыть](closeable-ru-67cd73fca69d.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд — Пространство имён XBSL: Std](std-c15458c2f5f0.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [Контекст](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Context_ru/).
