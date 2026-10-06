# Событие

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Event_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Event_ru/index.html
> SHA256: 6eeb9c840a9157956f47164b0ec6e8fe18c9d4004deb792a3cdbaae56f0c9bd8
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Событие` `Доступность: Сервер`

Описывает событие, на которое можно подписаться с помощью аннотации [Подписка](../../wiki/stdlib/subscription-ru-9e7e7a49ab5d.md). Объекты данного типа создаются на основе литерала события.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Литералы

Синтаксис: Событие{<ИмяТипа>.<ИмяСобытия>}. Где:

- <ИмяТипа> - имя типа
- <ИмяСобытия> - имя события

Поддерживаются следующие типы и события:

- <ИмяСправочника>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/data/catalogname-object-ru-8fd7b105e091.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/data/catalogname-object-ru-8fd7b105e091.md)
  - ПередУдалением
    
    [ПередУдалением](../../wiki/data/catalogname-object-ru-8fd7b105e091.md)
  - ПослеУдаления
    
    [ПослеУдаления](../../wiki/data/catalogname-object-ru-8fd7b105e091.md)
- <ИмяДокумента>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/data/documentname-object-ru-55639d28c4dc.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/data/documentname-object-ru-55639d28c4dc.md)
  - ПередУдалением
    
    [ПередУдалением](../../wiki/data/documentname-object-ru-55639d28c4dc.md)
  - ПослеУдаления
    
    [ПослеУдаления](../../wiki/data/documentname-object-ru-55639d28c4dc.md)
- <ИмяПланаОбмена>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/integration/exchangeplanname-object-ru-2882849e24b4.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/integration/exchangeplanname-object-ru-2882849e24b4.md)
  - ПередУдалением
    
    [ПередУдалением](../../wiki/integration/exchangeplanname-object-ru-2882849e24b4.md)
  - ПослеУдаления
    
    [ПослеУдаления](../../wiki/integration/exchangeplanname-object-ru-2882849e24b4.md)
- <ИмяХранилищаНастроек>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/data/settingsstoragename-object-ru-76dd064bfbbf.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/data/settingsstoragename-object-ru-76dd064bfbbf.md)
  - ПередУдалением
    
    [ПередУдалением](../../wiki/data/settingsstoragename-object-ru-76dd064bfbbf.md)
  - ПослеУдаления
    
    [ПослеУдаления](../../wiki/data/settingsstoragename-object-ru-76dd064bfbbf.md)
- <ИмяНабораКонстант>.Запись
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/stdlib/constantssetname-record-ru-0435fbfdf30e.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/stdlib/constantssetname-record-ru-0435fbfdf30e.md)
  - ПередУдалением
    
    [ПередУдалением](../../wiki/stdlib/constantssetname-record-ru-0435fbfdf30e.md)
  - ПослеУдаления
    
    [ПослеУдаления](../../wiki/stdlib/constantssetname-record-ru-0435fbfdf30e.md)
- <ИмяРегистраСведений>.НаборЗаписей
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/data/informationregistername-recordset-ru-ff0cb8e8f1d1.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/data/informationregistername-recordset-ru-ff0cb8e8f1d1.md)
- Пользователи.Объект (см.
  
  [Пользователи.Объект](../../wiki/stdlib/users-object-ru-5916412d6fa2.md)
  
  )
  
  - ПослеИзменения
  - ПослеПодключения
  - ПослеОтключения
- <ИмяКонтрактаСущности>.Объект (см.
  
  [ИмяКонтрактаСущности.Объект](../../wiki/data/entitycontractname-object-ru-9fb448fd439a.md)
  
  )
  
  - ПередЗаписью
  - ПослеЗаписи
  - ПередУдалением
  - ПослеУдаления
- <ИмяИнтегрируемогоПриложения>.Объект
  
  - ПередЗаписью
    
    [ПередЗаписью](../../wiki/stdlib/integrableapplicationname-object-ru-2facace672c0.md)
  - ПослеЗаписи
    
    [ПослеЗаписи](../../wiki/stdlib/integrableapplicationname-object-ru-2facace672c0.md)
  - ПередУдалением
    
    [ПередУдалением](../../wiki/stdlib/integrableapplicationname-object-ru-2facace672c0.md)
  - ПослеУдаления
    
    [ПослеУдаления](../../wiki/stdlib/integrableapplicationname-object-ru-2facace672c0.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
