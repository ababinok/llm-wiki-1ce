# ИзменяемоеСоответствие

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [mutablemap-ru-b0e92a5fc29d-9ee23e3c7c22ab4e](../../raw/text_10_0/mutablemap-ru-b0e92a5fc29d-9ee23e3c7c22ab4e.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Collections.

Имена для поиска: `ИзменяемоеСоответствие`, `MutableMap`, `Стд::Коллекции::ИзменяемоеСоответствие<ТипКлюча,ТипЗначения>`, `Std::Collections::MutableMap`.

## Обзор

ТипКлюча: тип ключей соответствия.

## Документированный контракт и примеры

`Стд::Коллекции::ИзменяемоеСоответствие<ТипКлюча,ТипЗначения>` `Доступность: КлиентИСервер`

ТипКлюча: тип ключей соответствия. ТипЗначения: тип значений соответствия.

Изменяемая коллекция пар ключ и значение, предоставляющее быстрое получение значения по ключу. Не содержит дубликатов ключей. Каждому ключу соответствует только одно значение. Позволяет изменять состав элементов, но не добавлять произвольные новые элементы.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: [КлючИЗначение](keyandvalue-ru-35bb7912a071.md)<KeyType, ValueType>

Возвращает пары ключ-значение в порядке добавления.

## Иерархия типа

*Базовые типы:* [Обходимое<КлючИЗначение<ТипКлюча, ТипЗначения>>](iterable-ru-283adb0cc9eb.md), [Объект](object-ru-9e351f286699.md), [ЧитаемоеСоответствие<ТипКлюча, ТипЗначения>](readablemap-ru-8fb134a1c222.md)

*Дочерние типы:* [Соответствие](map-ru-075f0ef55c6b.md)

---

## Методы

### Очистить

`Доступность: КлиентИСервер`

```
Очистить()
```

Удаляет все элементы соответствия.

---

### Удалить

`Доступность: КлиентИСервер`

```
Удалить(Ключ: ТипКлюча): ТипЗначения?
```

Удаляет элемент соответствия с ключом

`Ключ`

. Возвращает значение соответствовавшее удаленному ключу или

`Неопределено`

, если в соответствии не было такого ключа.

**Перегрузка** [Удалить(Ключ: ТипКлюча, Значение: ТипЗначения): Булево](mutablemap-ru-b0e92a5fc29d.md)

---

### Удалить

`Доступность: КлиентИСервер`

```
Удалить(
  Ключ: ТипКлюча,
  Значение: ТипЗначения
): Булево
```

Удаляет элемент соответствия с ключом

`Ключ`

и значением

`Значение`

. Возвращает признак изменения соответствия.

**Перегрузка** [Удалить(Ключ: ТипКлюча): ТипЗначения?](mutablemap-ru-b0e92a5fc29d.md)

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

[Единственный](iterable-ru-283adb0cc9eb.md)

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

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

### ЧитаемоеСоответствие

[ВСтроку](readablemap-ru-8fb134a1c222.md)

[Значения](readablemap-ru-8fb134a1c222.md)

[Ключи](readablemap-ru-8fb134a1c222.md)

[Получить](readablemap-ru-8fb134a1c222.md)

[ПолучитьИлиНеопределено](readablemap-ru-8fb134a1c222.md)

[ПолучитьИлиУмолчание](readablemap-ru-8fb134a1c222.md)

[ПолучитьИлиУмолчание](readablemap-ru-8fb134a1c222.md)

[Размер](readablemap-ru-8fb134a1c222.md)

[Содержит](readablemap-ru-8fb134a1c222.md)

[СодержитЗначение](readablemap-ru-8fb134a1c222.md)

[СодержитКлюч](readablemap-ru-8fb134a1c222.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Коллекции — Пространство имён XBSL: Std](collections-74c7e94d2756.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ИзменяемоеСоответствие](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/MutableMap_ru/).
