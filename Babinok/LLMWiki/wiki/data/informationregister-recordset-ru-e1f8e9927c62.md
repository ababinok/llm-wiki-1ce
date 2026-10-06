# РегистрСведений.НаборЗаписей

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [informationregister-recordset-ru-e1f8e9927c62-96d7b5a1ea798bc5](../../raw/text-10.0/informationregister-recordset-ru-e1f8e9927c62-96d7b5a1ea798bc5.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / InformationRegisters.

Имена для поиска: `РегистрСведений.НаборЗаписей`, `InformationRegister.RecordSet`, `Стд::РегистрыСведений::РегистрСведений.НаборЗаписей`, `Std::InformationRegisters::InformationRegister.RecordSet`.

## Обзор

Базовый тип для всех типов наборов записей регистров сведений.

## Документированный контракт и примеры

`Стд::РегистрыСведений::РегистрСведений.НаборЗаписей` `Доступность: Сервер`

Базовый тип для всех типов наборов записей регистров сведений.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Обходит записи набора.

## Иерархия типа

*Базовые типы:* [Обходимое<ItemType>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md), [Сущность.НаборЗаписей](entity-recordset-ru-f931a479ef6d.md), [ЧитаемаяКоллекция<ItemType>](../stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемыйМассив<Сущность.Запись>](../stdlib/readablearray-ru-6bae9724f632.md)

*Дочерние типы:* [ИмяПодчиненногоРегистраСведений.НаборЗаписей.Данные](subordinatedinformationregistername-recordset-data-ru-a5411bc8afb5.md), [ИмяПодчиненногоРегистраСведений.НаборЗаписей](subordinatedinformationregistername-recordset-ru-2530ab1eeede.md), [ИмяРегистраСведений.НаборЗаписей.Данные](informationregistername-recordset-data-ru-7d58b014161b.md), [ИмяРегистраСведений.НаборЗаписей](informationregistername-recordset-ru-ff0cb8e8f1d1.md)

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

Переопределение: [Фильтр](informationregister-recordset-ru-e1f8e9927c62.md)

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

**Переопределение** [Сущность.НаборЗаписей::Прочитать](entity-recordset-ru-f931a479ef6d.md)

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

[ВМассив](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствие](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСКлючами](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСоЗначениями](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВоМножество](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВсеСоответствуют](../stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[ДляКаждого](../stdlib/iterable-ru-283adb0cc9eb.md)

[ДляКаждого](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиНеопределено](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕстьСоответствия](../stdlib/iterable-ru-283adb0cc9eb.md)

[КакПоследовательность](../stdlib/iterable-ru-283adb0cc9eb.md)

[Максимум](../stdlib/iterable-ru-283adb0cc9eb.md)

[МаксимумПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Минимум](../stdlib/iterable-ru-283adb0cc9eb.md)

[МинимумПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[НетСоответствий](../stdlib/iterable-ru-283adb0cc9eb.md)

[Объединить](../stdlib/iterable-ru-283adb0cc9eb.md)

[Объединить](../stdlib/iterable-ru-283adb0cc9eb.md)

[Первый](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиНеопределено](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПотомСортироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Преобразовать](../stdlib/iterable-ru-283adb0cc9eb.md)

[Преобразовать](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПропуститьНеопределено](../stdlib/iterable-ru-283adb0cc9eb.md)

[Пусто](../stdlib/iterable-ru-283adb0cc9eb.md)

[Свернуть](../stdlib/iterable-ru-283adb0cc9eb.md)

[Свернуть](../stdlib/iterable-ru-283adb0cc9eb.md)

[Соединить](../stdlib/iterable-ru-283adb0cc9eb.md)

[Сортировать](../stdlib/iterable-ru-283adb0cc9eb.md)

[Сортировать](../stdlib/iterable-ru-283adb0cc9eb.md)

[СортироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Среднее](../stdlib/iterable-ru-283adb0cc9eb.md)

[СреднееИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[Сумма](../stdlib/iterable-ru-283adb0cc9eb.md)

[Уникальные](../stdlib/iterable-ru-283adb0cc9eb.md)

[УникальныеПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Фильтровать](../stdlib/iterable-ru-283adb0cc9eb.md)

[Фильтровать](../stdlib/iterable-ru-283adb0cc9eb.md)

[ФильтроватьПоТипу](../stdlib/iterable-ru-283adb0cc9eb.md)

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

### Сущность.НаборЗаписей

[Прочитать](entity-recordset-ru-f931a479ef6d.md) [(Переопределение)](informationregister-recordset-ru-e1f8e9927c62.md)

### ЧитаемаяКоллекция

[Единственный](../stdlib/readablecollection-ru-7f954f257c24.md)

[Размер](../stdlib/readablecollection-ru-7f954f257c24.md)

[Содержит](../stdlib/readablecollection-ru-7f954f257c24.md)

[СодержитВсе](../stdlib/readablecollection-ru-7f954f257c24.md)

### ЧитаемыйМассив

[ВСтроку](../stdlib/readablearray-ru-6bae9724f632.md)

[Граница](../stdlib/readablearray-ru-6bae9724f632.md)

[Найти](../stdlib/readablearray-ru-6bae9724f632.md)

[НайтиСКонца](../stdlib/readablearray-ru-6bae9724f632.md)

[ПодМассив](../stdlib/readablearray-ru-6bae9724f632.md)

[Получить](../stdlib/readablearray-ru-6bae9724f632.md)

[Последний](../stdlib/readablearray-ru-6bae9724f632.md)

[СодержитВсе](../stdlib/readablearray-ru-6bae9724f632.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::РегистрыСведений — Пространство имён XBSL: Std](informationregisters-96689ab02657.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [РегистрСведений.НаборЗаписей](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/InformationRegisters/InformationRegister.RecordSet_ru/).
