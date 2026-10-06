# ИзменяемыйМассив

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/MutableArray_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Collections/MutableArray_ru/index.html
> SHA256: 7be46a704cb5f52b56cd4591841185a9573685de37ceed606b2b2dc7d1456935
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Коллекции::ИзменяемыйМассив<ТипЭлемента>` `Доступность: КлиентИСервер`

ТипЭлемента: тип элементов массива.

Изменяемый массив, в которой каждому элементу соответствует свой индекс. Поддерживает дубликаты элементов. Позволяет изменять состав и порядок элементов массива, но не добавлять произвольные новые элементы в массив.

Индексация начинается с 0. Методы, принимающие диапазоны значений, не включают верхний индекс. Числовое значение индекса должно лежать в диапазоне 0.. 2147483647. При работе методов с индексами могут быть выброшены исключения:

- [ИсключениеИндексВнеГраниц](../../wiki/stdlib/indexoutofboundsexception-ru-2b34a623369c.md)
  
  - при выходе индекса за допустимый диапазон,
- [ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)
  
  - если индекс начальный индекс >= конечного индекса.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Возвращает элементы массива в порядке следования индексов.

## Иерархия типа

*Базовые типы:* [ИзменяемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [Обходимое<ТипЭлемента>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ТипЭлемента>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ЧитаемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемыйМассив<ТипЭлемента>](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

*Дочерние типы:* [Массив](../../wiki/stdlib/array-ru-f0659b9628e1.md)

---

## Методы

### ВставитьНовый

`Доступность: КлиентИСервер`

```
<ItemType это Конструируемое> ВставитьНовый(Индекс: Число): ТипЭлемента
```

Вставляет новый элемент в массив по указанному индексу

`Индекс`

, путем вызова конструктора без параметров. Возвращает созданный элемент.

#### Исключения

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - если тип элементов составной или абстрактный

---

### ДобавитьНовый

`Доступность: КлиентИСервер`

```
<ItemType это Конструируемое> ДобавитьНовый(): ТипЭлемента
```

Добавляет новый элемент в конец массива, путем вызова конструктора без параметров. Возвращает созданный элемент.

#### Исключения

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - если тип элементов составной или абстрактный

---

### Перевернуть

`Доступность: КлиентИСервер`

```
Перевернуть(
  От: Число = 0,
  До: Число)
```

Меняет местами элементы массива, находящиеся в диапазоне индексов, начиная с

`От`

до

`До`

, не включая конечный. Значением по умолчанию конечного индекса

`До`

является размер массива.

Прошлые имена: Развернуть

---

### Удалить

`Доступность: КлиентИСервер`

```
Удалить(
  Элемент: ТипЭлемента,
  ТолькоПервый: Булево
): Булево
```

Удаляет элемент

`Элемент`

из массива. Если

`ТолькоПервый`

истина, то будет удалено только первое вхождение элемента в массив. Возвращает признак того, что массив был изменен.

**Перегрузка** [ИзменяемаяКоллекция::Удалить(Элемент: ТипЭлемента): Булево](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

---

### УдалитьДиапазон

`Доступность: КлиентИСервер`

```
УдалитьДиапазон(
  От: Число,
  До: Число)
```

Удаляет значения из массива в заданном диапазоне индексов с

`От`

до

`До`

, не включая конечный. Значением по умолчанию конечного индекса

`До`

является размер массива.

---

### УдалитьПоИндексу

`Доступность: КлиентИСервер`

```
УдалитьПоИндексу(Индекс: Число): ТипЭлемента
```

Удаляет элемент по индексу

`Индекс`

и возвращает его.

Прошлые имена: УдалитьПоИндексу

---

## Список унаследованных методов

### ИзменяемаяКоллекция

[Очистить](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[Удалить](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьВсе](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьКроме](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

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
