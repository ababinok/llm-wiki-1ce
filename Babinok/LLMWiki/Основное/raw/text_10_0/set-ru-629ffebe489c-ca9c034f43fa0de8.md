# Множество

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/Set_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Collections/Set_ru/index.html
> SHA256: 18c0f9a0b777a7d05cf0d9460f56acb847fd532ca74f30aafacaf9f5398e35fc
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Коллекции::Множество<ТипЭлемента>` `Доступность: КлиентИСервер`

ТипЭлемента: тип элементов множества.

Изменяемая коллекция, не содержащая дубликатов. Обеспечивает быструю проверку вхождения элемента в коллекцию.

**Сравнение**

Структурное

- множества считаются равными, если их размер совпадает, а так же каждое из множеств содержит все элементы другого.
- типы множеств при этом не учитываются.

**Обход в цикле**

Тип: ТипЭлемента

Возвращает элементы множества в порядке следования добавления.

## Иерархия типа

*Базовые типы:* [ИзменяемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [ИзменяемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [ИзменяемоеМножество<ТипЭлемента>](../../wiki/stdlib/mutableset-ru-b964190c77e2.md), [Коллекция<ТипЭлемента>](../../wiki/stdlib/collection-ru-3bc2025a9946.md), [Обходимое<ТипЭлемента>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ТипЭлемента>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Обходимое<ТипЭлемента>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ЧитаемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемаяКоллекция<ТипЭлемента>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md), [ЧитаемоеМножество<ТипЭлемента>](../../wiki/stdlib/readableset-ru-6c31217c511a.md)

---

## Примеры

**Сравнение**

```xbsl
знч ОбычноеМножество = новый Множество<Число>({1, 2, 3})
знч ЧитаемоеМножество = новый ЧитаемоеМножество<Объект>({3, 2, 1})
  
знч Равны = ОбычноеМножество == ЧитаемоеМножество // Истина
```

---

## Литералы

Синтаксис (краткий): `{ элемент_0, ..., элемент_n }`, тип элементов множества выводится автоматически (если возможно). Синтаксис (с указанием типов элементов): `<ИмяТипа>{ элемент_0, ..., элемент_n }`.

### Примеры

```xbsl
знч ПустоеМножествоЧисел1: Множество<Число> = {} // сработал вывод типа
знч ПустоеМножествоЧисел2 = <Число>{}
знч МножествоЧисел = {1, 2, 3}
знч МножествоОбъектов = <Объект>{1, 2, True}
```

---

## Конструкторы

### Множество

`Доступность: КлиентИСервер`

```
Множество()
```

Создает пустое множество.

**Перегрузка** [Множество(Обходимое: Обходимое<ТипЭлемента>)](../../wiki/stdlib/set-ru-629ffebe489c.md)

#### Примеры

```xbsl
знч Множество = новый Множество<Число>()
// равносильный литерал: <Число>{}
```

---

### Множество

`Доступность: КлиентИСервер`

```
Множество(Обходимое: Обходимое<ТипЭлемента>)
```

Конструктор копирования. Копирует элементы переданного

`Обходимое`

в новое множество.

**Перегрузка** [Множество()](../../wiki/stdlib/set-ru-629ffebe489c.md)

---

## Список унаследованных методов

### ИзменяемаяКоллекция

[Очистить](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[Удалить](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьВсе](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьКроме](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md)

### Коллекция

[Добавить](../../wiki/stdlib/collection-ru-3bc2025a9946.md)

[ДобавитьВсе](../../wiki/stdlib/collection-ru-3bc2025a9946.md)

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

### ЧитаемоеМножество

[ВСтроку](../../wiki/stdlib/readableset-ru-6c31217c511a.md)

[Объединение](../../wiki/stdlib/readableset-ru-6c31217c511a.md)

[Пересечение](../../wiki/stdlib/readableset-ru-6c31217c511a.md)

[Разность](../../wiki/stdlib/readableset-ru-6c31217c511a.md)

[СимметрическаяРазность](../../wiki/stdlib/readableset-ru-6c31217c511a.md)
