# Событие

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [event-ru-f6f2c9295cb4-32fe863db91fa2bc](../../raw/text-10.0/event-ru-f6f2c9295cb4-32fe863db91fa2bc.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std.

Имена для поиска: `Событие`, `Event`, `Стд::Событие`, `Std::Event`.

## Обзор

Описывает событие, на которое можно подписаться с помощью аннотации [Подписка](subscription-ru-9e7e7a49ab5d.md).

## Документированный контракт и примеры

`Стд::Событие` `Доступность: Сервер`

Описывает событие, на которое можно подписаться с помощью аннотации [Подписка](subscription-ru-9e7e7a49ab5d.md). Объекты данного типа создаются на основе литерала события.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

---

## Литералы

Синтаксис: Событие{<ИмяТипа>.<ИмяСобытия>}. Где:

- <ИмяТипа> - имя типа
- <ИмяСобытия> - имя события

Поддерживаются следующие типы и события:

- <ИмяСправочника>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../data/catalogname-object-ru-8fd7b105e091.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../data/catalogname-object-ru-8fd7b105e091.md)
  - ПередУдалением
    
    [ПередУдалением](../data/catalogname-object-ru-8fd7b105e091.md)
  - ПослеУдаления
    
    [ПослеУдаления](../data/catalogname-object-ru-8fd7b105e091.md)
- <ИмяДокумента>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../data/documentname-object-ru-55639d28c4dc.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../data/documentname-object-ru-55639d28c4dc.md)
  - ПередУдалением
    
    [ПередУдалением](../data/documentname-object-ru-55639d28c4dc.md)
  - ПослеУдаления
    
    [ПослеУдаления](../data/documentname-object-ru-55639d28c4dc.md)
- <ИмяПланаОбмена>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../integration/exchangeplanname-object-ru-2882849e24b4.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../integration/exchangeplanname-object-ru-2882849e24b4.md)
  - ПередУдалением
    
    [ПередУдалением](../integration/exchangeplanname-object-ru-2882849e24b4.md)
  - ПослеУдаления
    
    [ПослеУдаления](../integration/exchangeplanname-object-ru-2882849e24b4.md)
- <ИмяХранилищаНастроек>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../data/settingsstoragename-object-ru-76dd064bfbbf.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../data/settingsstoragename-object-ru-76dd064bfbbf.md)
  - ПередУдалением
    
    [ПередУдалением](../data/settingsstoragename-object-ru-76dd064bfbbf.md)
  - ПослеУдаления
    
    [ПослеУдаления](../data/settingsstoragename-object-ru-76dd064bfbbf.md)
- <ИмяНабораКонстант>.Запись
  
  - ПередЗаписью
    
    [ПередЗаписью](constantssetname-record-ru-0435fbfdf30e.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](constantssetname-record-ru-0435fbfdf30e.md)
  - ПередУдалением
    
    [ПередУдалением](constantssetname-record-ru-0435fbfdf30e.md)
  - ПослеУдаления
    
    [ПослеУдаления](constantssetname-record-ru-0435fbfdf30e.md)
- <ИмяРегистраСведений>.НаборЗаписей
  
  - ПередЗаписью
    
    [ПередЗаписью](../data/informationregistername-recordset-ru-ff0cb8e8f1d1.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../data/informationregistername-recordset-ru-ff0cb8e8f1d1.md)
- Пользователи.Объект (см.
  
  [Пользователи.Объект](users-object-ru-5916412d6fa2.md)
  
  )
  
  - ПослеИзменения
  - ПослеПодключения
  - ПослеОтключения
- <ИмяКонтрактаСущности>.Объект (см.
  
  [ИмяКонтрактаСущности.Объект](../data/entitycontractname-object-ru-9fb448fd439a.md)
  
  )
  
  - ПередЗаписью
  - ПослеЗаписи
  - ПередУдалением
  - ПослеУдаления
- <ИмяИнтегрируемогоПриложения>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](integrableapplicationname-object-ru-2facace672c0.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](integrableapplicationname-object-ru-2facace672c0.md)
  - ПередУдалением
    
    [ПередУдалением](integrableapplicationname-object-ru-2facace672c0.md)
  - ПослеУдаления
    
    [ПослеУдаления](integrableapplicationname-object-ru-2facace672c0.md)

### Примеры

Подписка на событие ПередЗаписью справочника Товары:

```xbsl
@Подписка(Событие{Товары.Объект.ПередЗаписью})
метод ЦеновойУчетПодписка(Источник: Товары.Данные,
                  До: Товары.Данные,
                  Параметры: Товары.ПараметрыЗаписи)
    // Обработка события
;
```

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд — Пространство имён XBSL: Std](std-c15458c2f5f0.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [Событие](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Event_ru/).
