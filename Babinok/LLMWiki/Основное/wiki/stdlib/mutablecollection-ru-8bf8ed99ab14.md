# ИзменяемаяКоллекция

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [mutablecollection-ru-8bf8ed99ab14-cd9504cab2ac530f](../../raw/text_10_0/mutablecollection-ru-8bf8ed99ab14-cd9504cab2ac530f.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Collections.

Имена для поиска: `ИзменяемаяКоллекция`, `MutableCollection`, `Стд::Коллекции::ИзменяемаяКоллекция<ТипЭлемента>`, `Std::Collections::MutableCollection`.

## Обзор

ТипЭлемента: тип элементов коллекции.

## Документированный контракт и примеры

`Стд::Коллекции::ИзменяемаяКоллекция<ТипЭлемента>` `Доступность: КлиентИСервер`

ТипЭлемента: тип элементов коллекции.

Изменяемое объединение конечного числа элементов. Позволяет изменять состав элементов, но не добавлять произвольные новые элементы.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Возвращает элементы в порядке добавления.

## Иерархия типа

*Базовые типы:* [Обходимое<ТипЭлемента>](iterable-ru-283adb0cc9eb.md), [Объект](object-ru-9e351f286699.md), [ЧитаемаяКоллекция<ТипЭлемента>](readablecollection-ru-7f954f257c24.md)

*Дочерние типы:* [ИзменяемоеМножество](mutableset-ru-b964190c77e2.md), [ИзменяемыйМассив](mutablearray-ru-37e20d0db52d.md), [Коллекция](collection-ru-3bc2025a9946.md)

---

## Методы

### Очистить

`Доступность: КлиентИСервер`

```
Очистить()
```

Удаляет все элементы из коллекции.

---

### Удалить

`Доступность: КлиентИСервер`

```
Удалить(Элемент: ТипЭлемента): Булево
```

Удаляет указанный

`Элемент`

из коллекции. Возвращает признак того, что коллекция была изменена.

---

### УдалитьВсе

`Доступность: КлиентИСервер`

```
УдалитьВсе(Обходимое: Обходимое<ТипЭлемента>): Булево
```

Удаляет из коллекции все элементы

`Обходимое`

. Возвращает признак того, что коллекция была изменена.

#### Примеры

```xbsl
[1, 2, 1].УдалитьВсе([1])         // Истина   [2]
[1, 2].УдалитьВсе([3, 4])         // Ложь     [1, 2]
```

---

### УдалитьКроме

`Доступность: КлиентИСервер`

```
УдалитьКроме(Обходимое: Обходимое<ТипЭлемента>): Булево
```

Оставляет в коллекции только элементы

`Обходимое`

. Возвращает признак того, что коллекция была изменена.

#### Примеры

```xbsl
[1, 2, 1].УдалитьКроме([1])         // Истина   [1, 1]
[1, 2].УдалитьКроме([1, 2, 3])      // Ложь     [1, 2]
```

---

## Список унаследованных методов

### Обходимое

[ВМассив](iterable-ru-283adb0cc9eb.md)

[ВСоответствие](iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСКлючами](iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСоЗначениями](iterable-ru-283adb0cc9eb.md)

[ВоМножество](iterable-ru-283adb0cc9eb.md)

[ВсеСоответствуют](iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](iterable-ru-283adb0cc9eb.md)

[ДляКаждого](iterable-ru-283adb0cc9eb.md)

[ДляКаждого](iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиНеопределено](iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ЕстьСоответствия](iterable-ru-283adb0cc9eb.md)

[КакПоследовательность](iterable-ru-283adb0cc9eb.md)

[Максимум](iterable-ru-283adb0cc9eb.md)

[МаксимумПо](iterable-ru-283adb0cc9eb.md)

[Минимум](iterable-ru-283adb0cc9eb.md)

[МинимумПо](iterable-ru-283adb0cc9eb.md)

[НетСоответствий](iterable-ru-283adb0cc9eb.md)

[Объединить](iterable-ru-283adb0cc9eb.md)

[Объединить](iterable-ru-283adb0cc9eb.md)

[Первый](iterable-ru-283adb0cc9eb.md)

[ПервыйИлиНеопределено](iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ПотомСортироватьПо](iterable-ru-283adb0cc9eb.md)

[Преобразовать](iterable-ru-283adb0cc9eb.md)

[Преобразовать](iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](iterable-ru-283adb0cc9eb.md)

[ПропуститьНеопределено](iterable-ru-283adb0cc9eb.md)

[Пусто](iterable-ru-283adb0cc9eb.md)

[Свернуть](iterable-ru-283adb0cc9eb.md)

[Свернуть](iterable-ru-283adb0cc9eb.md)

[Соединить](iterable-ru-283adb0cc9eb.md)

[Сортировать](iterable-ru-283adb0cc9eb.md)

[Сортировать](iterable-ru-283adb0cc9eb.md)

[СортироватьПо](iterable-ru-283adb0cc9eb.md)

[Среднее](iterable-ru-283adb0cc9eb.md)

[СреднееИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[Сумма](iterable-ru-283adb0cc9eb.md)

[Уникальные](iterable-ru-283adb0cc9eb.md)

[УникальныеПо](iterable-ru-283adb0cc9eb.md)

[Фильтровать](iterable-ru-283adb0cc9eb.md)

[Фильтровать](iterable-ru-283adb0cc9eb.md)

[ФильтроватьПоТипу](iterable-ru-283adb0cc9eb.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

### ЧитаемаяКоллекция

[Единственный](readablecollection-ru-7f954f257c24.md)

[Размер](readablecollection-ru-7f954f257c24.md)

[Содержит](readablecollection-ru-7f954f257c24.md)

[СодержитВсе](readablecollection-ru-7f954f257c24.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Коллекции — Пространство имён XBSL: Std](collections-74c7e94d2756.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ИзменяемаяКоллекция](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/MutableCollection_ru/).
