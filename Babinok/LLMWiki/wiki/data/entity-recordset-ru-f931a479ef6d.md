# Сущность.НаборЗаписей

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [entity-recordset-ru-f931a479ef6d-a625c38ab4c00e43](../../raw/text-10.0/entity-recordset-ru-f931a479ef6d-a625c38ab4c00e43.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Entities.

Имена для поиска: `Сущность.НаборЗаписей`, `Entity.RecordSet`, `Стд::Сущности::Сущность.НаборЗаписей`, `Std::Entities::Entity.RecordSet`.

## Обзор

Базовый тип для наборов записей необъектных сущностей.

## Документированный контракт и примеры

`Стд::Сущности::Сущность.НаборЗаписей` `Доступность: Сервер`

Базовый тип для наборов записей необъектных сущностей.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

## Иерархия типа

*Базовые типы:* [Обходимое<ItemType>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ЧитаемаяКоллекция<ItemType>](../stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемыйМассив<Сущность.Запись>](../stdlib/readablearray-ru-6bae9724f632.md)

*Дочерние типы:* [РегистрНакопления.НаборЗаписей](accumulationregister-recordset-ru-4f1184452493.md), [РегистрСведений.НаборЗаписей](informationregister-recordset-ru-e1f8e9927c62.md)

---

## Свойства

### Фильтр

`Доступность: Сервер` `ТолькоЧтение`

```
Фильтр: Сущность.НаборЗаписей.Фильтр
```

Фильтр набора записей.

---

## Методы

### Прочитать

`Доступность: Сервер`

```
Прочитать()
```

Считывает набор записей из базы данных. Если набор (в памяти) был не пустым - все записи из него удаляются. Если фильтр не инициализирован - будет выдана ошибки о неиницализированности фильтра.

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
- [Стд::Сущности — Пространство имён XBSL: Std](entities-7b2acb4f9eee.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [Сущность.НаборЗаписей](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/Entity.RecordSet_ru/).
