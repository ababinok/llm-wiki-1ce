# {ИмяРегистраНакопления}.НаборЗаписей

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/AccumulationRegisterName.RecordSet_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/AccumulationRegisterName.RecordSet_ru/index.html
> SHA256: 97c2c180a0d08de4db04bd45422d2ecf9c2ece3316c21c6a1d214ef2aa8a9a23
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяРегистраНакопления}.НаборЗаписей` `Доступность: Сервер`

Набор записей предназначен для записи и чтения из БД набора записей со значениями измерений соответствующими установленному фильтру (см. свойство [Фильтр](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)).

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

## Иерархия типа

*Базовые типы:* [ИзменяемаяКоллекция<ItemType>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [ИзменяемаяКоллекция<ItemType>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [ИзменяемыйМассив<ItemType>](../../wiki/stdlib/mutablearray-ru-37e20d0db52d.md), [Коллекция<ItemType>](../../wiki/stdlib/collection-ru-3bc2025a9946.md), [Массив<ИмяРегистраНакопления.Запись>](../../wiki/stdlib/array-ru-f0659b9628e1.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [РегистрНакопления.НаборЗаписей](../../wiki/data/accumulationregister-recordset-ru-4f1184452493.md), [Сущность.НаборЗаписей](../../wiki/data/entity-recordset-ru-f931a479ef6d.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ItemType>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемыйМассив<ItemType>](../../wiki/stdlib/readablearray-ru-6bae9724f632.md), [ЧитаемыйМассив<Сущность.Запись>](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ЗаписатьЗаказы(Регистратор: ЗаказКлиента.Ссылка, ЗагруженныеЗаказы: Обходимое<ЗаказыКлиентов.Запись>)
    знч НаборЗаписей = новый ЗаказыКлиентов.НаборЗаписей()
    НаборЗаписей.Фильтр.Установить(Регистратор = Регистратор)
    НаборЗаписей.ДобавитьВсе(ЗагруженныеЗаказы) 
    НаборЗаписей.Записать()
;
```

---

## Конструкторы

### {ИмяРегистраНакопления}.НаборЗаписей

`Доступность: Сервер`

```
{ИмяРегистраНакопления}.НаборЗаписей()
```

Конструктор по умолчанию - создаёт пустой набор записей. Фильтр не инициализирован. Активность набора имеет значение Истина.

---

## Свойства

### Фильтр

`Доступность: Сервер` `ТолькоЧтение`

```
Фильтр: {ИмяРегистраНакопления}.НаборЗаписей.Фильтр
```

Фильтр набора записей. Свойство унаследовано от базового типа, только уточнён тип.

Переопределение: [Фильтр](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

---

## Методы

### ДобавитьЗапись

`Версия 10.0 и выше`

`Доступность: Сервер`

```
@ИменованныеПараметры
ДобавитьЗапись(
  Период: ДатаВремя,
  ВидЗаписи: ВидЗаписиРегистраНакопления,
  <Измерение1>: <ТипИзмерения1> = <ЗначениеПоУмолчаниюИзмерения1>,
  ....<ИзмерениеN>: <ТипИзмеренияN> = <ЗначениеПоУмолчаниюИзмеренияN>,
  <Ресурс1>: <ТипРесурса1> = <ЗначениеПоУмолчаниюРесурса1>,
  ...<РесурсN>: <ТипРесурсаN> = <ЗначениеПоУмолчаниюРесурсаN>,
  <Реквизит1>: <ТипРеквизита1> = <ЗначениеПоУмолчаниюРеквизита1>,
  ....<РеквизитN>: <ТипРеквизитаN> = <ЗначениеПоУмолчаниюРеквизитаN>)
```

>

Вызов возможен только с именованными параметрами

Добавляет в набор новую запись и заполняет значения её полей в соответствии с установленным в наборе записей фильтром и переданными значениями. Стандартное поле `ВидЗаписи` доступно только для регистра остатков. Если фильтр не инициализирован (см. описание свойство [Инициализирован](../../wiki/data/entity-recordset-filter-ru-54579d6f4b8c.md) в фильтре набора записей регистра накопления) - будет выдана ошибки о неиницализированности фильтра. Активность записи устанавливается в соответствии с установленной активностью для набора. По умолчанию активность набора имеет значение Истина. Добавленная запись возвращается в качестве результата вызова.

---

### ДобавитьЗапись

`Версия 9.0 и ниже`

`Доступность: Сервер`

```
@ИменованныеПараметры
ДобавитьЗапись(
  Период: ДатаВремя,
  ВидЗаписи: ВидЗаписиРегистраНакопления,
  ИмяИзмерения: {ИмяСправочника}.Ссылка?,
  ИмяРесурса: Число
): {ИмяРегистраНакопления}.Запись
```

Метод заменен на

[ДобавитьЗапись](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

.

---

### Записать

`Доступность: Сервер`

```
Записать(Замещать: Булево = Истина)
```

Записывает набор записей в базу данных. Если фильтр не инициализирован (см. описание свойство

[Инициализирован](../../wiki/data/entity-recordset-filter-ru-54579d6f4b8c.md)

в фильтре набора записей регистра накопления) - будет выдана ошибки о неиницализированности фильтра. При наличии в наборе записей не соответствующих фильтру - будет выдана ошибка о несоответствии записи фильтру. При наличии в наборе записей со значением стандартного поля

`Активность`

не соответствующих значению установленному для набора записей - будет выдана ошибка о несоответствии записи набору. Не допускается наличие в наборе одной и той-же записи более одного раза, так как для каждой записи при сохранении в базу данных устанавливается индекс обеспечивающий уникальность в разрезе регистратора. В этом случае будет выдана ошибка. Если значение параметра

`Замещать`

=

`Истина`

, перед записью из таблицы базы данных будут удалены все записи соответствующие фильтру. Если значение параметра

`Замещать`

=

`Ложь`

, новые записи будут дописываться к существующим. После записи в режиме

`Замещать`

=

`Ложь`

набор записей очищается.

**Перегрузка** [Записать(Замещать: Булево = Истина, ПараметрыЗаписи: ИмяРегистраНакопления.ПараметрыЗаписи)](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

---

### Записать

`Версия 9.0 и ниже`

`Доступность: Сервер`

```
Записать(
  Замещать: Булево = Истина,
  ПараметрыЗаписи: {ИмяРегистраНакопления}.ПараметрыЗаписи)
```

Метод заменен на

[Записать](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

.

---

### УстановитьАктивность

`Доступность: Сервер`

```
УстановитьАктивность(Активность: Булево)
```

Устанавливает значение свойства Активность у всех записей, входящих в набор.

---

## Обработчики

### ПередЗаписью

`Версия 10.0 и выше`

`Доступность: Сервер`

```
ПередЗаписью(
  Замещать: Булево,
  ПараметрыЗаписи: {ИмяРегистраНакопления}.ПараметрыЗаписи)
```

Вызывается при вызове метода

[Записать](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

, после того как начата транзакция и захвачена блокировка. Значение параметра

`Замещать`

соответствуют значению переданному при вызове метода

[Записать](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

. Параметр

`ПараметрыЗаписи`

содержит объявленные в объекте параметры записи (см. ИмяРегистраНакопления.ПараметрыЗаписи).

---

### ПослеЗаписи

`Версия 10.0 и выше`

`Доступность: Сервер`

```
ПослеЗаписи(
  Замещать: Булево,
  ПараметрыЗаписи: {ИмяРегистраНакопления}.ПараметрыЗаписи)
```

Вызывается в транзакции при вызове метода

[Записать](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

, после записи элемента в БД. Значение параметра

`Замещать`

соответствуют значению переданному при вызове метода

[Записать](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

. Параметр

`ПараметрыЗаписи`

содержит объявленные в объекте параметры записи (см. ИмяРегистраНакопления.ПараметрыЗаписи).

---

### ПередЗаписью

`Версия 9.0 и ниже`

`Доступность: Сервер`

```
ПередЗаписью(
  Замещать: Булево = Истина,
  ПараметрыЗаписи: {ИмяРегистраНакопления}.ПараметрыЗаписи)
```

Метод заменен на

[ПередЗаписью](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

.

---

### ПослеЗаписи

`Версия 9.0 и ниже`

`Доступность: Сервер`

```
ПослеЗаписи(
  Замещать: Булево = Истина,
  ПараметрыЗаписи: {ИмяРегистраНакопления}.ПараметрыЗаписи)
```

Метод заменен на

[ПослеЗаписи](../../wiki/data/accumulationregistername-recordset-ru-b4bf21480f3e.md)

.

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

### РегистрНакопления.НаборЗаписей

[Прочитать](../../wiki/data/accumulationregister-recordset-ru-4f1184452493.md)

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
