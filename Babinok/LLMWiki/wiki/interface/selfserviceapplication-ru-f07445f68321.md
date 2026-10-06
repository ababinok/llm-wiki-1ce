# ПриложениеСамообслуживания

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [selfserviceapplication-ru-f07445f68321-89349707ddccc908](../../raw/text-10.0/selfserviceapplication-ru-f07445f68321-89349707ddccc908.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Пользователи / SelfService / Interface.

Имена для поиска: `ПриложениеСамообслуживания`, `SelfServiceApplication`, `Стд::Пользователи::Самообслуживание::Интерфейс::ПриложениеСамообслуживания`, `Std::Users::SelfService::Interface::SelfServiceApplication`.

## Обзор

Встроенное приложение самообслуживания пользователя.

## Документированный контракт и примеры

`Стд::Пользователи::Самообслуживание::Интерфейс::ПриложениеСамообслуживания` `Доступность: Клиент`

Встроенное приложение самообслуживания пользователя. Доступно по адресу "Путь_К_Приложению/self-service"

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [КлиентскоеПриложение](clientapplication-ru-b046bbeb06bc.md), [Компонент](component-ru-bad1c84be995.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ПроизвольноеКлиентскоеПриложение](customclientapplication-ru-4315de55a773.md)

---

## Методы

### Открыть

`Доступность: Клиент` `Статический`

```
Открыть(ОткрыватьВНовомОкне: Булево = Истина)
```

Открывает Приложение

`ОткрыватьВНовомОкне`

- если

`Ложь`

, то откроется в текущем окне, иначе в новой вкладке браузера.

---

## Список унаследованных методов

### КлиентскоеПриложение

[ДобавитьВИсториюПереходов](clientapplication-ru-b046bbeb06bc.md)

[ЗаменитьВИсторииПереходов](clientapplication-ru-b046bbeb06bc.md)

[ПолучитьОтносительныйПуть](clientapplication-ru-b046bbeb06bc.md)

[ПолучитьСостояниеПерехода](clientapplication-ru-b046bbeb06bc.md)

[ПолучитьТекущуюЦветовуюСхему](clientapplication-ru-b046bbeb06bc.md)

### Компонент

[Активировать](component-ru-bad1c84be995.md)

[ОтключитьОбработчикТаймера](component-ru-bad1c84be995.md)

[ПодключитьОбработчикТаймера](component-ru-bad1c84be995.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### КлиентскоеПриложение

[SeoОписание](clientapplication-ru-b046bbeb06bc.md), [ВебЧат](clientapplication-ru-b046bbeb06bc.md), [ВнешнийВебСайт](clientapplication-ru-b046bbeb06bc.md), [Заголовок](clientapplication-ru-b046bbeb06bc.md), [ОткрытьГлобальныйПоиск](clientapplication-ru-b046bbeb06bc.md), [ОткрытьИзбранноеПользователя](clientapplication-ru-b046bbeb06bc.md), [ОткрытьИсториюРаботыПользователя](clientapplication-ru-b046bbeb06bc.md), [ОткрытьНастройкиСистемыВзаимодействия](clientapplication-ru-b046bbeb06bc.md), [ОткрытьОбсуждения](clientapplication-ru-b046bbeb06bc.md), [ОткрытьЦентрУведомлений](clientapplication-ru-b046bbeb06bc.md), [ОтображатьИндикаторЗагрузки](clientapplication-ru-b046bbeb06bc.md), [ПараметрыКаноническогоUrl](clientapplication-ru-b046bbeb06bc.md), [ПереключитьЦветовуюСхему](clientapplication-ru-b046bbeb06bc.md), [ПереключитьЯзык](clientapplication-ru-b046bbeb06bc.md), [ПоказатьИнформациюОПриложении](clientapplication-ru-b046bbeb06bc.md), [Путь](clientapplication-ru-b046bbeb06bc.md), [РежимАутентификации](clientapplication-ru-b046bbeb06bc.md), [СпособОткрытияФормСущностей](clientapplication-ru-b046bbeb06bc.md), [ТемаОформления](clientapplication-ru-b046bbeb06bc.md)

### Компонент

[ВесПриРастягивании](component-ru-bad1c84be995.md), [Видимость](component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](component-ru-bad1c84be995.md), [Высота](component-ru-bad1c84be995.md), [Доступность](component-ru-bad1c84be995.md), [ЕстьНаведение](component-ru-bad1c84be995.md), [МаксимальнаяВысота](component-ru-bad1c84be995.md), [МаксимальнаяШирина](component-ru-bad1c84be995.md), [МинимальнаяВысота](component-ru-bad1c84be995.md), [МинимальнаяШирина](component-ru-bad1c84be995.md), [РастягиватьПоВертикали](component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](component-ru-bad1c84be995.md), [ТолькоЧтение](component-ru-bad1c84be995.md), [Ширина](component-ru-bad1c84be995.md), [ШиринаВКолонках](component-ru-bad1c84be995.md)

### ПроизвольноеКлиентскоеПриложение

[ВыравниваниеКопирайтаПоВертикали](customclientapplication-ru-4315de55a773.md), [ВыравниваниеКопирайтаПоГоризонтали](customclientapplication-ru-4315de55a773.md), [КомпонентОбластиФормы](customclientapplication-ru-4315de55a773.md), [ОтступПоВертикали](customclientapplication-ru-4315de55a773.md), [ОтступПоГоризонтали](customclientapplication-ru-4315de55a773.md), [Содержимое](customclientapplication-ru-4315de55a773.md)

## Список унаследованных событий

### КлиентскоеПриложение

[SeoОписание](clientapplication-ru-b046bbeb06bc.md), [ВебЧат](clientapplication-ru-b046bbeb06bc.md), [ВнешнийВебСайт](clientapplication-ru-b046bbeb06bc.md), [Заголовок](clientapplication-ru-b046bbeb06bc.md), [ОткрытьГлобальныйПоиск](clientapplication-ru-b046bbeb06bc.md), [ОткрытьИзбранноеПользователя](clientapplication-ru-b046bbeb06bc.md), [ОткрытьИсториюРаботыПользователя](clientapplication-ru-b046bbeb06bc.md), [ОткрытьНастройкиСистемыВзаимодействия](clientapplication-ru-b046bbeb06bc.md), [ОткрытьОбсуждения](clientapplication-ru-b046bbeb06bc.md), [ОткрытьЦентрУведомлений](clientapplication-ru-b046bbeb06bc.md), [ОтображатьИндикаторЗагрузки](clientapplication-ru-b046bbeb06bc.md), [ПараметрыКаноническогоUrl](clientapplication-ru-b046bbeb06bc.md), [ПереключитьЦветовуюСхему](clientapplication-ru-b046bbeb06bc.md), [ПереключитьЯзык](clientapplication-ru-b046bbeb06bc.md), [ПоказатьИнформациюОПриложении](clientapplication-ru-b046bbeb06bc.md), [Путь](clientapplication-ru-b046bbeb06bc.md), [РежимАутентификации](clientapplication-ru-b046bbeb06bc.md), [СпособОткрытияФормСущностей](clientapplication-ru-b046bbeb06bc.md), [ТемаОформления](clientapplication-ru-b046bbeb06bc.md)

### Компонент

[ВесПриРастягивании](component-ru-bad1c84be995.md), [Видимость](component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](component-ru-bad1c84be995.md), [Высота](component-ru-bad1c84be995.md), [Доступность](component-ru-bad1c84be995.md), [ЕстьНаведение](component-ru-bad1c84be995.md), [МаксимальнаяВысота](component-ru-bad1c84be995.md), [МаксимальнаяШирина](component-ru-bad1c84be995.md), [МинимальнаяВысота](component-ru-bad1c84be995.md), [МинимальнаяШирина](component-ru-bad1c84be995.md), [РастягиватьПоВертикали](component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](component-ru-bad1c84be995.md), [ТолькоЧтение](component-ru-bad1c84be995.md), [Ширина](component-ru-bad1c84be995.md), [ШиринаВКолонках](component-ru-bad1c84be995.md)

## See Also

- [Навигатор раздела](../security/overview.md)
- [Стд::Пользователи::Самообслуживание::Интерфейс — Пространство имён XBSL: Std / Пользователи / SelfService](interface-ca491feacdf0.md)
- [Ключи доступа и разрешения приложения](../security/access-keys-and-permissions.md)

Оригинал: [ПриложениеСамообслуживания](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Users/SelfService/Interface/SelfServiceApplication_ru/).
