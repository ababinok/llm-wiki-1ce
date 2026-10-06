# Коллекция

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [collection-ru-3bc2025a9946-fd9b2e4a925100d5](../../raw/text-10.0/collection-ru-3bc2025a9946-fd9b2e4a925100d5.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Collections.

Имена для поиска: `Коллекция`, `Collection`, `Стд::Коллекции::Коллекция<ТипЭлемента>`, `Std::Collections::Collection`.

## Обзор

ТипЭлемента: тип элементов коллекции.

## Документированный контракт и примеры

`Стд::Коллекции::Коллекция<ТипЭлемента>` `Доступность: КлиентИСервер`

ТипЭлемента: тип элементов коллекции.

Объединение конечного числа элементов.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Возвращает элементы в порядке добавления.

## Иерархия типа

*Базовые типы:* [ИзменяемаяКоллекция<ТипЭлемента>](mutablecollection-ru-8bf8ed99ab14.md), [Обходимое<ТипЭлемента>](iterable-ru-283adb0cc9eb.md), [Объект](object-ru-9e351f286699.md), [ЧитаемаяКоллекция<ТипЭлемента>](readablecollection-ru-7f954f257c24.md)

*Дочерние типы:* [Массив](array-ru-f0659b9628e1.md), [Множество](set-ru-629ffebe489c.md)

---

## Методы

### Добавить

`Доступность: КлиентИСервер`

```
Добавить(Элемент: ТипЭлемента): Булево
```

Добавляет указанный

`Элемент`

в коллекцию. Возвращает признак того, что коллекция была изменена.

---

### ДобавитьВсе

`Доступность: КлиентИСервер`

```
ДобавитьВсе(Обходимое: Обходимое<ТипЭлемента>): Булево
```

Добавляет в коллекцию все элементы

`Обходимое`

. Возвращает признак того, что коллекция была изменена.

---

## Список унаследованных методов

### ИзменяемаяКоллекция

[Очистить](mutablecollection-ru-8bf8ed99ab14.md)

[Удалить](mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьВсе](mutablecollection-ru-8bf8ed99ab14.md)

[УдалитьКроме](mutablecollection-ru-8bf8ed99ab14.md)

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

Оригинал: [Коллекция](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/Collection_ru/).
