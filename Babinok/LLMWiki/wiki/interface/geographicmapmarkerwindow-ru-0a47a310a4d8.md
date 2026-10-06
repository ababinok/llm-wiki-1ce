# ОкноМаркераГеографическойКарты

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [geographicmapmarkerwindow-ru-0a47a310a4d8-bf6022a5ceb7fcf6](../../raw/text-10.0/geographicmapmarkerwindow-ru-0a47a310a4d8-bf6022a5ceb7fcf6.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / GeographicMaps / Interface.

Имена для поиска: `ОкноМаркераГеографическойКарты`, `GeographicMapMarkerWindow`, `Стд::ГеографическиеКарты::Интерфейс::ОкноМаркераГеографическойКарты<ТипДанныхМаркера>`, `Std::GeographicMaps::Interface::GeographicMapMarkerWindow`.

## Обзор

ТипДанныхМаркера: Тип свойства `Данные` маркеров.

## Документированный контракт и примеры

`Стд::ГеографическиеКарты::Интерфейс::ОкноМаркераГеографическойКарты<ТипДанныхМаркера>` `Доступность: Клиент`

ТипДанныхМаркера: Тип свойства `Данные` маркеров. Параметр типа должен иметь значение по умолчанию или `Неопределено` в составе типов.

Абстрактный компонент базового окна маркера географической карты, который служит для отображения информации в окне на карте по нажатию на маркер.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Компонент](component-ru-bad1c84be995.md), [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ПроизвольноеОкноМаркераГеографическойКарты](geographicmapmarkercustomwindow-ru-80ef2d2e6c01.md), [СтандартноеОкноМаркераГеографическойКарты](geographicmapmarkerstandardwindow-ru-7b0ec3022514.md)

---

## Свойства

### Маркер

`Доступность: Клиент`

```
Маркер: МаркерГеографическойКарты<ТипДанныхМаркера>
```

Маркер на географической карте, к которому относится данное окно. Проставляется системой автоматически.

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
- [Стд::ГеографическиеКарты::Интерфейс — Пространство имён XBSL: Std / GeographicMaps](interface-1e2452ec5e9e.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [ОкноМаркераГеографическойКарты](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/GeographicMaps/Interface/GeographicMapMarkerWindow_ru/).
