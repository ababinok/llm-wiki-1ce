# ИзменяемоеСоответствие

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/MutableMap_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Collections/MutableMap_ru/index.html
> SHA256: 57ec1b74a595d66c531ae5ba0013418c2a26b3676c8a98d67922529953441ca4
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Коллекции::ИзменяемоеСоответствие<ТипКлюча,ТипЗначения>` `Доступность: КлиентИСервер`

ТипКлюча: тип ключей соответствия. ТипЗначения: тип значений соответствия.

Изменяемая коллекция пар ключ и значение, предоставляющее быстрое получение значения по ключу. Не содержит дубликатов ключей. Каждому ключу соответствует только одно значение. Позволяет изменять состав элементов, но не добавлять произвольные новые элементы.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: [КлючИЗначение](../../wiki/stdlib/keyandvalue-ru-35bb7912a071.md)<KeyType, ValueType>

Возвращает пары ключ-значение в порядке добавления.

## Иерархия типа

*Базовые типы:* [Обходимое<КлючИЗначение<ТипКлюча, ТипЗначения>>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ЧитаемоеСоответствие<ТипКлюча, ТипЗначения>](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

*Дочерние типы:* [Соответствие](../../wiki/stdlib/map-ru-075f0ef55c6b.md)

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

**Перегрузка** [Удалить(Ключ: ТипКлюча, Значение: ТипЗначения): Булево](../../wiki/stdlib/mutablemap-ru-b0e92a5fc29d.md)

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

**Перегрузка** [Удалить(Ключ: ТипКлюча): ТипЗначения?](../../wiki/stdlib/mutablemap-ru-b0e92a5fc29d.md)

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

[Единственный](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

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

### ЧитаемоеСоответствие

[ВСтроку](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[Значения](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[Ключи](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[Получить](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[ПолучитьИлиНеопределено](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[ПолучитьИлиУмолчание](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[ПолучитьИлиУмолчание](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[Размер](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[Содержит](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[СодержитЗначение](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

[СодержитКлюч](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)
