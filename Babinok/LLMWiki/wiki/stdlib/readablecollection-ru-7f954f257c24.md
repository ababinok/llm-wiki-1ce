# ЧитаемаяКоллекция

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [readablecollection-ru-7f954f257c24-cbe85ac7c6feab75](../../raw/text-10.0/readablecollection-ru-7f954f257c24-cbe85ac7c6feab75.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Collections.

Имена для поиска: `ЧитаемаяКоллекция`, `ReadableCollection`, `Стд::Коллекции::ЧитаемаяКоллекция<ТипЭлемента>`, `Std::Collections::ReadableCollection`.

## Обзор

ТипЭлемента: тип элементов коллекции.

## Документированный контракт и примеры

`Стд::Коллекции::ЧитаемаяКоллекция<ТипЭлемента>` `Доступность: КлиентИСервер`

ТипЭлемента: тип элементов коллекции.

Коллекция элементов, доступная только на чтение.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Возвращает элементы коллекции в порядке добавления.

## Иерархия типа

*Базовые типы:* [Обходимое<ТипЭлемента>](iterable-ru-283adb0cc9eb.md), [Объект](object-ru-9e351f286699.md)

*Дочерние типы:* [ИзменяемаяКоллекция](mutablecollection-ru-8bf8ed99ab14.md), [КоллекцияОтраженийЭлементовПроекта](projectelementsreflectioncollection-ru-189fccb75ec0.md), [ЧитаемоеМножество](readableset-ru-6c31217c511a.md), [ЧитаемыйМассив](readablearray-ru-6bae9724f632.md)

---

## Методы

### Единственный

`Доступность: КлиентИСервер`

```
Единственный(): ТипЭлемента
```

Возвращает единственный содержащийся в коллекции элемент.

#### Исключения

**[ИсключениеНедопустимоеСостояние](illegalstateexception-ru-4c1cc853b874.md)** - если нет элементов или элементов больше одного.

**Переопределение** [Обходимое::Единственный](iterable-ru-283adb0cc9eb.md)

---

### Размер

`Доступность: КлиентИСервер`

```
Размер(): Число
```

Возвращает количество элементов в коллекции.

---

### Содержит

`Доступность: КлиентИСервер`

```
Содержит(Элемент: Объект?): Булево
```

Проверяет, содержится ли в коллекции элемент

`Элемент`

.

---

### СодержитВсе

`Доступность: КлиентИСервер`

```
СодержитВсе(Обходимое: Обходимое<Объект?>): Булево
```

Проверяет, содержатся ли в коллекции все элементы

`Обходимое`

. Метод не учитывает число повторов элементов.

#### Примеры

```xbsl
[1, 2, 3].СодержитВсе([1, 1, 2])    // Истина
[1, 2, 3].СодержитВсе([1, 4])       // Ложь
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

[Единственный](iterable-ru-283adb0cc9eb.md) [(Переопределение)](readablecollection-ru-7f954f257c24.md)

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

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Коллекции — Пространство имён XBSL: Std](collections-74c7e94d2756.md)
- [Коллекции и точные контракты стандартной библиотеки](collections-and-contracts.md)

Оригинал: [ЧитаемаяКоллекция](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/ReadableCollection_ru/).
