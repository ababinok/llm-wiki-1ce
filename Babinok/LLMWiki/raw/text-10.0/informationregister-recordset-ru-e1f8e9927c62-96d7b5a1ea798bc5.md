# РегистрСведений.НаборЗаписей

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/InformationRegisters/InformationRegister.RecordSet_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/InformationRegisters/InformationRegister.RecordSet_ru/index.html
> SHA256: 296dca25a14858ef0efdb24d49ba3e2dd284a26b365be5074410a2361cb57bd2
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::РегистрыСведений::РегистрСведений.НаборЗаписей` `Доступность: Сервер`

Базовый тип для всех типов наборов записей регистров сведений.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Обходит записи набора.

## Иерархия типа

*Базовые типы:* [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Сущность.НаборЗаписей](../../wiki/data/entity-recordset-ru-f931a479ef6d.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемыйМассив<Сущность.Запись>](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

*Дочерние типы:* [ИмяПодчиненногоРегистраСведений.НаборЗаписей.Данные](../../wiki/data/subordinatedinformationregistername-recordset-data-ru-a5411bc8afb5.md), [ИмяПодчиненногоРегистраСведений.НаборЗаписей](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md), [ИмяРегистраСведений.НаборЗаписей.Данные](../../wiki/data/informationregistername-recordset-data-ru-7d58b014161b.md), [ИмяРегистраСведений.НаборЗаписей](../../wiki/data/informationregistername-recordset-ru-ff0cb8e8f1d1.md)

---

## Примеры

**Обход в цикле**

```xbsl
метод ОбработатьЦены()
    пер НаборЗаписей = новый ЦеныТоваров.НаборЗаписей()
    НаборЗаписей.Фильтр.Установить() 
    НаборЗаписей.Прочитать()
    для Запись из НаборЗаписей
        // действия с записью
    ;
;
```

---

## Свойства

### Фильтр

`Доступность: Сервер` `ТолькоЧтение`

```
Фильтр: РегистрСведений.НаборЗаписей.Фильтр
```

Фильтр набора записей - значения измерений, по которым определяется попадает запись в набор записей или нет.

Переопределение: [Фильтр](../../wiki/data/informationregister-recordset-ru-e1f8e9927c62.md)

#### Примеры

```xbsl
метод СоздатьФильтр(ПользовательСсылка: Пользователи.Ссылка): ЦеныТоваров.НаборЗаписей.Фильтр 
    пер НаборЗаписей = новый ЦеныТоваров.НаборЗаписей()
    НаборЗаписей.Фильтр.Установить(Пользователь = ПользовательСсылка)
    возврат НаборЗаписей.Фильтр
;
```

---

## Методы

### Прочитать

`Доступность: Сервер`

```
Прочитать()
```

Считывает набор записей из базы данных.

Если набор (в памяти) был не пустым - все записи из него удаляются. Если фильтр не инициализирован - будет выдана ошибки о неиницализированности фильтра.

**Переопределение** [Сущность.НаборЗаписей::Прочитать](../../wiki/data/entity-recordset-ru-f931a479ef6d.md)

#### Примеры

```xbsl
метод ПрочитатьВсеЦены()
    пер НаборЗаписей = новый ЦеныТоваров.НаборЗаписей()
    НаборЗаписей.Фильтр.Установить() 
    НаборЗаписей.Прочитать()
;
```

---

## Список унаследованных методов

### Обходимое

[ВМассив](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствие](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСКлючами](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСоЗначениями](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ВоМножество](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ВсеСоответствуют](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ДляКаждого](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ДляКаждого](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиНеопределено](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ЕстьСоответствия](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[КакПоследовательность](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Максимум](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[МаксимумПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Минимум](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[МинимумПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[НетСоответствий](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Объединить](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Объединить](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Первый](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиНеопределено](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПотомСортироватьПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Преобразовать](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Преобразовать](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ПропуститьНеопределено](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Пусто](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Свернуть](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Свернуть](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Соединить](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Сортировать](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Сортировать](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[СортироватьПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Среднее](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[СреднееИлиУмолчание](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Сумма](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Уникальные](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[УникальныеПо](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Фильтровать](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[Фильтровать](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

[ФильтроватьПоТипу](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### Сущность.НаборЗаписей

[Прочитать](../../wiki/data/entity-recordset-ru-f931a479ef6d.md) [(Переопределение)](../../wiki/data/informationregister-recordset-ru-e1f8e9927c62.md)

### ЧитаемаяКоллекция

[Единственный](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

[Размер](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

[Содержит](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

[СодержитВсе](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

### ЧитаемыйМассив

[ВСтроку](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[Граница](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[Найти](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[НайтиСКонца](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[ПодМассив](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[Получить](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[Последний](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

[СодержитВсе](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)
