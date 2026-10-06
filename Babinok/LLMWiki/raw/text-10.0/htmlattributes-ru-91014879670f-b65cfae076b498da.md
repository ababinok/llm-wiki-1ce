# АтрибутыHtml

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HtmlDocument/HtmlAttributes_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/HtmlDocument/HtmlAttributes_ru/index.html
> SHA256: 76c246dc46e098325da322630f0e302ce412981baac755b605b9f017e08744cd
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ДокументHtml::АтрибутыHtml` `Доступность: Сервер`

Коллекция атрибутов элемента Html.

**Сравнение**

Ссылочное

Структурное

## Иерархия типа

*Базовые типы:* [Обходимое<АтрибутHtml>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

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

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

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

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - если переданное имя атрибута не удовлетворяет стандарту.

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

[Пусто](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md) [(Переопределение)](../../wiki/data/htmlattributes-ru-91014879670f.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/data/htmlattributes-ru-91014879670f.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
