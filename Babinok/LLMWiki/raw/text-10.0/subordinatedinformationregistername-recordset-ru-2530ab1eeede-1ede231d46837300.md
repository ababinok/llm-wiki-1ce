# {ИмяПодчиненногоРегистраСведений}.НаборЗаписей

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SubordinatedInformationRegisterName.RecordSet_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SubordinatedInformationRegisterName.RecordSet_ru/index.html
> SHA256: 8b79b818ab0a35b99366886c599cd48f29fa6cc0af36ff245699cfa2acf9f944
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПодчиненногоРегистраСведений}.НаборЗаписей` `Доступность: Сервер`

Предназначен для записи и чтения из базы данных набора записей со значениями измерений, соответствующими установленному фильтру (см. свойство [Фильтр](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)).

Порядок следования записей в наборе не сохраняется между записью и последующим чтением из базы данных.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

## Иерархия типа

*Базовые типы:* [ИзменяемаяКоллекция<ItemType>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [ИзменяемаяКоллекция<ItemType>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [ИзменяемыйМассив<ItemType>](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md), [Коллекция<ItemType>](../../wiki/stdlib/collection-ru-3bc2025a9946.md), [Массив<ИмяПодчиненногоРегистраСведений.Запись>](../../wiki/stdlib/array-ru-f0659b9628e1.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [РегистрСведений.НаборЗаписей](../../wiki/data/informationregister-recordset-ru-e1f8e9927c62.md), [Сущность.НаборЗаписей](../../wiki/data/entity-recordset-ru-f931a479ef6d.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемыйМассив<ItemType>](../../wiki/stdlib/readablearray-ru-6bae9724f632.md), [ЧитаемыйМассив<Сущность.Запись>](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ПолучитьНаборЗаписей(Регистратор: ПоступлениеТоваров.Ссылка): Цены.НаборЗаписей
    пер НаборЗаписей = новый Цены.НаборЗаписей()
    НаборЗаписей.Фильтр.Установить(Регистратор) 
    НаборЗаписей.Прочитать()
    возврат НаборЗаписей
;
```

---

## Конструкторы

### {ИмяПодчиненногоРегистраСведений}.НаборЗаписей

`Доступность: Сервер`

```
ИмяПодчиненногоРегистраСведений.НаборЗаписей()
```

---

## Свойства

### Фильтр

`Доступность: Сервер` `ТолькоЧтение`

```
Фильтр: {ИмяПодчиненногоРегистраСведений}.НаборЗаписей.Фильтр
```

Свойство унаследовано от базового типа, только уточнен тип.

Переопределение: [Фильтр](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)

---

## Методы

### ДобавитьЗапись

`Доступность: Сервер`

```
@ИменованныеПараметры
ДобавитьЗапись(
  Период: <ТипПериода>,
  Активность: <Булево>,
  <Измерение1>: <ТипИзмерения1> = <ЗначениеПоУмолчаниюИзмерения1>,
  ....<ИзмерениеN>: <ТипИзмеренияN> = <ЗначениеПоУмолчаниюИзмеренияN>,
  <Ресурс1>: <ТипРесурса1> = <ЗначениеПоУмолчаниюРесурса1>,
  ...<РесурсN>: <ТипРесурсаN> = <ЗначениеПоУмолчаниюРесурсаN>,
  <Реквизит1>: <ТипРеквизита1> = <ЗначениеПоУмолчаниюРеквизита1>,
  ....<РеквизитN>: <ТипРеквизитаN> = <ЗначениеПоУмолчаниюРеквизитаN>)
```

>

Вызов возможен только с именованными параметрами

Добавляет в набор новую запись и заполняет значения ее измерений (и стандартных полей `Период` и `Активность`, если они есть) в соответствии с установленным в наборе записей фильтром и переданными значениями.

Если фильтр не инициализирован (см. описание свойства [Инициализирован](../../wiki/data/entity-recordset-filter-ru-54579d6f4b8c.md) в фильтре набора записей регистра сведений) — будет выдана соответствующая ошибка. Добавленная запись возвращается в качестве результата вызова.

---

### Записать

`Доступность: Сервер`

```
Записать(Замещать: Булево = Истина)
```

Записывает набор записей в базу данных.

Если фильтр не инициализирован (см. описание свойства [Инициализирован](../../wiki/data/entity-recordset-filter-ru-54579d6f4b8c.md) в фильтре набора записей регистра сведений), будет выдана соответствующая ошибка. При наличии в наборе записей, не соответствующих фильтру, будет выдана ошибка о несоответствии записи фильтру. При наличии в наборе записей с одинаковыми ключами записей, будет выдана ошибка о нарушении уникальности записей.

Если значение параметра `Замещать` = `Истина`, перед записью из таблицы базы данных будут удалены все записи, соответствующие фильтру (если фильтр пустой, но инициализированный — из таблицы будут удалены вообще все записи).

Если значение параметра `Замещать` = `Ложь`, новые записи будут дописываться к существующим. Если при этом будет обнаружено нарушение уникальности записей в таблице базы данных, будет выдана ошибка о нарушении уникальности записей. При этом если вызов выполнялся в объемлющей транзакции, транзакция становится непригодной для продолжения работы.

После записи в режиме `Замещать` = `Ложь` набор записей очищается.

**Перегрузка** [Записать(Замещать: Булево = Истина, ПараметрыЗаписи: ИмяПодчиненногоРегистраСведений.ПараметрыЗаписи)](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)

---

### {ИмяПодчиненногоРегистраСведений}.НаборЗаписей

`Доступность: Сервер`

```
ИмяПодчиненногоРегистраСведений.НаборЗаписей()
```

Конструктор по умолчанию — создает пустой набор записей.

---

### УстановитьАктивность

`Доступность: Сервер`

```
УстановитьАктивность(Активность: Булево)
```

Устанавливает значение свойства

`Активность`

у набора записей.

#### Примеры

```xbsl
метод УстановитьАктивность()
    знч НаборЗаписей = новый Цены.НаборЗаписей()
    НаборЗаписей.УстановитьАктивность(Ложь)
;
```

---

## Обработчики

### ПередЗаписью

`Доступность: Сервер`

```
ПередЗаписью(Замещать: Булево)
```

Вызывается при вызове метода

[Записать](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)

, после того как начата транзакция и захвачена блокировка. Значение параметра

`Замещать`

соответствуют значению, переданному при вызове метода

[Записать](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)

.

#### Примеры

Подписка на событие, объявленная в общем модуле:

```xbsl
@Подписка(Событие{Цены.НаборЗаписей.ПередЗаписью})
метод ПодпискаПередЗаписью(Источник: Цены.НаборЗаписей.Данные,
                Заменить: Булево,
                Параметры: Цены.ПараметрыЗаписи)
    // Обработка события
;
```

---

### ПослеЗаписи

`Доступность: Сервер`

```
ПослеЗаписи(Замещать: Булево)
```

Вызывается в транзакции при вызове метода

[Записать](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)

после записи элемента в базу данных. Значение параметра

`Замещать`

соответствуют значению, переданному при вызове метода

[Записать](../../wiki/data/subordinatedinformationregistername-recordset-ru-2530ab1eeede.md)

.

#### Примеры

Подписка на событие, объявленная в общем модуле:

```xbsl
@Подписка(Событие{Цены.НаборЗаписей.ПослеЗаписи})
метод ПодпискаПослеЗаписи(Источник: Цены.НаборЗаписей.Данные,
                Заменить: Булево,
                Параметры: Цены.ПараметрыЗаписи)
    // Обработка события
;
```

---

## Список унаследованных методов

### ИзменяемаяКоллекция

[Очистить](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[Удалить](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьВсе](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьКроме](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

### ИзменяемыйМассив

[ВставитьНовый](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md)

[ДобавитьНовый](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md)

[Перевернуть](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md)

[Удалить](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md)

[УдалитьДиапазон](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md)

[УдалитьПоИндексу](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md)

### Коллекция

[Добавить](../../wiki/stdlib/collection-ru-3bc2025a9946.md)

[ДобавитьВсе](../../wiki/stdlib/collection-ru-3bc2025a9946.md)

### Массив

[Вставить](../../wiki/stdlib/array-ru-f0659b9628e1.md)

[ВставитьВсе](../../wiki/stdlib/array-ru-f0659b9628e1.md)

[Установить](../../wiki/stdlib/array-ru-f0659b9628e1.md)

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

### РегистрСведений.НаборЗаписей

[Прочитать](../../wiki/data/informationregister-recordset-ru-e1f8e9927c62.md)

### Сущность.НаборЗаписей

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

## Список унаследованных событий

### Сущность.НаборЗаписей

[Фильтр](../../wiki/data/entity-recordset-ru-f931a479ef6d.md)
