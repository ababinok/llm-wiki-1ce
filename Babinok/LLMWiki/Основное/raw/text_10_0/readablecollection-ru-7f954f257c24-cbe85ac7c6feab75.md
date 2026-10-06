# ЧитаемаяКоллекция

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Collections/ReadableCollection_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Collections/ReadableCollection_ru/index.html
> SHA256: c3fd5be6e5c9eceee2748ca080304ff5856e58d73dcbee74b600490d1e9829e7
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Коллекции::ЧитаемаяКоллекция<ТипЭлемента>` `Доступность: КлиентИСервер`

ТипЭлемента: тип элементов коллекции.

Коллекция элементов, доступная только на чтение.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Возвращает элементы коллекции в порядке добавления.

## Иерархия типа

*Базовые типы:* [Обходимое<ТипЭлемента>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИзменяемаяКоллекция](../../wiki/stdlib/mutablecollection-ru-8bf8ed99ab14.md), [КоллекцияОтраженийЭлементовПроекта](../../wiki/stdlib/projectelementsreflectioncollection-ru-189fccb75ec0.md), [ЧитаемоеМножество](../../wiki/stdlib/readableset-ru-6c31217c511a.md), [ЧитаемыйМассив](../../wiki/stdlib/readablearray-ru-6bae9724f632.md)

---

## Методы

### Единственный

`Доступность: КлиентИСервер`

```
Единственный(): ТипЭлемента
```

Возвращает единственный содержащийся в коллекции элемент.

#### Исключения

**[ИсключениеНедопустимоеСостояние](../../wiki/stdlib/illegalstateexception-ru-4c1cc853b874.md)** - если нет элементов или элементов больше одного.

**Переопределение** [Обходимое::Единственный](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md)

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

[Единственный](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md) [(Переопределение)](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
