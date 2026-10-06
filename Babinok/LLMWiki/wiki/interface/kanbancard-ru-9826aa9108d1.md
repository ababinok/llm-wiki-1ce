# КанбанКарточка

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [kanbancard-ru-9826aa9108d1-949ab16f9e96d24e](../../raw/text-10.0/kanbancard-ru-9826aa9108d1-949ab16f9e96d24e.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Interface / KanbanBoard.

Имена для поиска: `КанбанКарточка`, `KanbanCard`, `Стд::Интерфейс::КанбанДоска::КанбанКарточка<ТипДанных>`, `Std::Interface::KanbanBoard::KanbanCard`.

## Обзор

*Базовые типы:* [Компонент](component-ru-bad1c84be995.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::Интерфейс::КанбанДоска::КанбанКарточка<ТипДанных>` `Доступность: Клиент`

ТипДанных: Тип данных карточки

Компонент карточки канбан-доски

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Компонент](component-ru-bad1c84be995.md), [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ПроизвольнаяКанбанКарточка](customkanbancard-ru-670bed1ce6ee.md), [СтандартнаяКанбанКарточка](standardkanbancard-ru-70fa3cbeb207.md)

---

## Свойства

### ДанныеСтроки

`Доступность: Клиент` `ТолькоЧтение`

```
ДанныеСтроки: ТипДанных
```

Строка из источника данных, соответствующая карточке

---

## Список унаследованных методов

### Компонент

[Активировать](component-ru-bad1c84be995.md)

[ОтключитьОбработчикТаймера](component-ru-bad1c84be995.md)

[ПодключитьОбработчикТаймера](component-ru-bad1c84be995.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Компонент

[ВесПриРастягивании](component-ru-bad1c84be995.md), [Видимость](component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](component-ru-bad1c84be995.md), [Высота](component-ru-bad1c84be995.md), [Доступность](component-ru-bad1c84be995.md), [ЕстьНаведение](component-ru-bad1c84be995.md), [МаксимальнаяВысота](component-ru-bad1c84be995.md), [МаксимальнаяШирина](component-ru-bad1c84be995.md), [МинимальнаяВысота](component-ru-bad1c84be995.md), [МинимальнаяШирина](component-ru-bad1c84be995.md), [РастягиватьПоВертикали](component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](component-ru-bad1c84be995.md), [ТолькоЧтение](component-ru-bad1c84be995.md), [Ширина](component-ru-bad1c84be995.md), [ШиринаВКолонках](component-ru-bad1c84be995.md)

## Список унаследованных событий

### Компонент

[ПриНаведении](component-ru-bad1c84be995.md), [ПриПеретаскивании](component-ru-bad1c84be995.md), [ПриПотереНаведения](component-ru-bad1c84be995.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Интерфейс::КанбанДоска — Пространство имён XBSL: Std / Interface](kanbanboard-83a5601376bb.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [КанбанКарточка](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/KanbanBoard/KanbanCard_ru/).
