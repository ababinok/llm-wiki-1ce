# АтрибутыHtml

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [htmlattributes-ru-91014879670f-b65cfae076b498da](../../raw/text-10.0/htmlattributes-ru-91014879670f-b65cfae076b498da.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / HtmlDocument.

Имена для поиска: `АтрибутыHtml`, `HtmlAttributes`, `Стд::ДокументHtml::АтрибутыHtml`, `Std::HtmlDocument::HtmlAttributes`.

## Обзор

*Базовые типы:* [Обходимое<АтрибутHtml>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::ДокументHtml::АтрибутыHtml` `Доступность: Сервер`

Коллекция атрибутов элемента Html.

**Сравнение**

Ссылочное

Структурное

## Иерархия типа

*Базовые типы:* [Обходимое<АтрибутHtml>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

```xbsl
метод КоллекцияАтрибутовЭлементаHtml(Элемент: ЭлементHtml)
    // Дано Элемент.ВнешнийКод() <div id="app-switcher" class="aui-dropdown2 aui-style-default" role="menu"></div>
    пер Результат = ""
    для Атрибут из Элемент.Атрибуты
        Результат += Атрибут.Имя + " : " + Атрибут.Значение + "\н"
    ;
    // Результат будет равен
    // id : app-switcher
    // class : aui-dropdown2 aui-style-default 
    // role : menu
;
```

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строку представления данной коллекции в коде

**Переопределение** [Объект::ВСтроку](../stdlib/object-ru-9e351f286699.md)

---

### Вставить

`Доступность: Сервер`

```
Вставить(
  Имя: Строка,
  Значение: Булево|Строка)
```

Вставить значение атрибута (булево для html5 атрибутов), имя атрибута приводится в lowercase. Если атрибут уже существует, то значение заменяется. Если в значении для html5 булевого атрибута передана Ложь, то атрибут будет удален из коллекции (и из элемента).

#### Исключения

**[ИсключениеНедопустимыйАргумент](../stdlib/illegalargumentexception-ru-fc532bf88932.md)** - если переданное имя атрибута не удовлетворяет стандарту.

---

### ЕстьЗначение

`Доступность: Сервер`

```
ЕстьЗначение(Имя: Строка): Булево
```

Есть ли установленное значение для атрибута. Имя на соответствие стандарту не анализируется.

---

### Получить

`Доступность: Сервер`

```
Получить(Имя: Строка): Строка?
```

Получить атрибут по имени без чувствительности к регистру или

`Неопределено`

- если атрибут не найден. Имя на соответствие стандарту не анализируется.

---

### Пусто

`Доступность: Сервер`

```
Пусто(): Булево
```

Признак того, что у элемента нет атрибутов.

---

### Размер

`Доступность: Сервер`

```
Размер(): Число
```

Количество атрибутов у элемента.

---

### Удалить

`Доступность: Сервер`

```
Удалить(Имя: Строка)
```

Удалить атрибут и его значение без чувствительности к регистру имени атрибута. Имя на соответствие стандарту не анализируется.

---

## Список унаследованных методов

### Обходимое

[ВМассив](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствие](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСКлючами](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСоЗначениями](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВоМножество](../stdlib/iterable-ru-283adb0cc9eb.md)

[ВсеСоответствуют](../stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[ДляКаждого](../stdlib/iterable-ru-283adb0cc9eb.md)

[ДляКаждого](../stdlib/iterable-ru-283adb0cc9eb.md)

[Единственный](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиНеопределено](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ЕстьСоответствия](../stdlib/iterable-ru-283adb0cc9eb.md)

[КакПоследовательность](../stdlib/iterable-ru-283adb0cc9eb.md)

[Максимум](../stdlib/iterable-ru-283adb0cc9eb.md)

[МаксимумПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Минимум](../stdlib/iterable-ru-283adb0cc9eb.md)

[МинимумПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[НетСоответствий](../stdlib/iterable-ru-283adb0cc9eb.md)

[Объединить](../stdlib/iterable-ru-283adb0cc9eb.md)

[Объединить](../stdlib/iterable-ru-283adb0cc9eb.md)

[Первый](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиНеопределено](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПотомСортироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Преобразовать](../stdlib/iterable-ru-283adb0cc9eb.md)

[Преобразовать](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](../stdlib/iterable-ru-283adb0cc9eb.md)

[ПропуститьНеопределено](../stdlib/iterable-ru-283adb0cc9eb.md)

[Пусто](../stdlib/iterable-ru-283adb0cc9eb.md) [(Переопределение)](htmlattributes-ru-91014879670f.md)

[Свернуть](../stdlib/iterable-ru-283adb0cc9eb.md)

[Свернуть](../stdlib/iterable-ru-283adb0cc9eb.md)

[Соединить](../stdlib/iterable-ru-283adb0cc9eb.md)

[Сортировать](../stdlib/iterable-ru-283adb0cc9eb.md)

[Сортировать](../stdlib/iterable-ru-283adb0cc9eb.md)

[СортироватьПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Среднее](../stdlib/iterable-ru-283adb0cc9eb.md)

[СреднееИлиУмолчание](../stdlib/iterable-ru-283adb0cc9eb.md)

[Сумма](../stdlib/iterable-ru-283adb0cc9eb.md)

[Уникальные](../stdlib/iterable-ru-283adb0cc9eb.md)

[УникальныеПо](../stdlib/iterable-ru-283adb0cc9eb.md)

[Фильтровать](../stdlib/iterable-ru-283adb0cc9eb.md)

[Фильтровать](../stdlib/iterable-ru-283adb0cc9eb.md)

[ФильтроватьПоТипу](../stdlib/iterable-ru-283adb0cc9eb.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](htmlattributes-ru-91014879670f.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::ДокументHtml — Пространство имён XBSL: Std](htmldocument-3aa09cdfb98c.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [АтрибутыHtml](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HtmlDocument/HtmlAttributes_ru/).
