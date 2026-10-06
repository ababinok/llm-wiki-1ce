# ВстроеннаяВебСтраница1СПредприятие

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [embedded1centerprisewebpage-ru-beb590d93db9-0d5e716419fdb80a](../../raw/text-10.0/embedded1centerprisewebpage-ru-beb590d93db9-0d5e716419fdb80a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Interface / ClientApplication.

Имена для поиска: `ВстроеннаяВебСтраница1СПредприятие`, `Embedded1CEnterpriseWebPage`, `Стд::Интерфейс::КлиентскоеПриложение::ВстроеннаяВебСтраница1СПредприятие`, `Std::Interface::ClientApplication::Embedded1CEnterpriseWebPage`.

## Обзор

Осуществляет взаимодействие с встроенной веб-страницей 1С внутри приложения типа [СтандартноеКлиентскоеПриложениеСРазделами](standardclientapplicationwithsections-ru-2bf3e285c484.md).

## Документированный контракт и примеры

`Стд::Интерфейс::КлиентскоеПриложение::ВстроеннаяВебСтраница1СПредприятие` `Доступность: Клиент`

Осуществляет взаимодействие с встроенной веб-страницей 1С внутри приложения типа [СтандартноеКлиентскоеПриложениеСРазделами](standardclientapplicationwithsections-ru-2bf3e285c484.md).

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ВстроеннаяВебСтраница](embeddedwebpage-ru-948b3b8bf499.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### ВстроеннаяВебСтраница1СПредприятие

`Доступность: Клиент`

```
ВстроеннаяВебСтраница1СПредприятие()
```

Создает новый объект

[ВстроеннаяВебСтраница1СПредприятие](embedded1centerprisewebpage-ru-beb590d93db9.md)

.

---

## События

### ПриЗакрытии

`Доступность: Клиент`

```
ПриЗакрытии: (
  ВстроеннаяВебСтраница1СПредприятие,
  СобытиеКомпонента)->ничто
```

Подключает обработчик, вызываемый при получении от встроенной веб-страницы информации о ее остановке.

---

## Список унаследованных методов

### ВстроеннаяВебСтраница

[Активировать](embeddedwebpage-ru-948b3b8bf499.md)

[Остановить](embeddedwebpage-ru-948b3b8bf499.md)

[ОтправитьСообщение](embeddedwebpage-ru-948b3b8bf499.md)

[ПоказатьСостояниеЗагрузки](embeddedwebpage-ru-948b3b8bf499.md)

[СкрытьСостояниеЗагрузки](embeddedwebpage-ru-948b3b8bf499.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ВстроеннаяВебСтраница

[Url](embeddedwebpage-ru-948b3b8bf499.md), [Активно](embeddedwebpage-ru-948b3b8bf499.md), [Данные](embeddedwebpage-ru-948b3b8bf499.md), [Запущено](embeddedwebpage-ru-948b3b8bf499.md), [Ид](embeddedwebpage-ru-948b3b8bf499.md), [Изображение](embeddedwebpage-ru-948b3b8bf499.md), [КомпонентСостоянияЗагрузки](embeddedwebpage-ru-948b3b8bf499.md), [Представление](embeddedwebpage-ru-948b3b8bf499.md)

## Список унаследованных событий

### ВстроеннаяВебСтраница

[ПриНачалеЗагрузки](embeddedwebpage-ru-948b3b8bf499.md), [ПриОткрытии](embeddedwebpage-ru-948b3b8bf499.md), [ПриПолученииСообщения](embeddedwebpage-ru-948b3b8bf499.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Интерфейс::КлиентскоеПриложение — Пространство имён XBSL: Std / Interface](clientapplication-03d27ceca705.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [ВстроеннаяВебСтраница1СПредприятие](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/ClientApplication/Embedded1CEnterpriseWebPage_ru/).
