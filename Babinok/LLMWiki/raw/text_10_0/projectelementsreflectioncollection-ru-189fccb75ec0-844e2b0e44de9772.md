# КоллекцияОтраженийЭлементовПроекта

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Reflection/ProjectElementsReflectionCollection_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Reflection/ProjectElementsReflectionCollection_ru/index.html
> SHA256: 8758fed56fd7ae1c993504061954c5a667284120acbfe4a2c6eda7929ee3263d
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Отражение::КоллекцияОтраженийЭлементовПроекта` `Доступность: Сервер`

Коллекция элементов проекта предоставляет способ обхода элементов проекта и поиска элементов проекта по имени или виду элемента проекта

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: ТипЭлемента

Доступно использование в цикле для..из Элементом итерации является ОтражениеЭлементаПроекта

## Иерархия типа

*Базовые типы:* [Обходимое<ItemType>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ЧитаемаяКоллекция<ОтражениеЭлементаПроекта>](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

---

## Операция []

`Только чтение`

```
[Ключ: Строка]: ОтражениеЭлементаПроекта
```

Получение элемента проекта по имени

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - если элемент проекта с указанным именем не найден

### Пример

```xbsl
метод НайтиСправочникТовары(Подсистема: ОтражениеПодсистемыПроекта): ОтражениеОбъектнойСущности?
    знч Справочник = Подсистема.Элементы["Товары"]
    если Справочник.ВидЭлемента != ВидЭлементаПроекта.Справочник
        выбросить новый ИсключениеНедопустимыйАргумент("Справочник с именем Товары не найден")
    ;
    
    возврат Справочник как ОтражениеОбъектнойСущности
;
```

---

## Методы

### Найти

`Доступность: Сервер`

```
Найти(Имя: Строка): ОтражениеЭлементаПроекта?
```

Найти элемент проекта по имени

---

### ПолучитьВсе

`Доступность: Сервер`

```
ПолучитьВсе<ТипЭлемента>(): ЧитаемыйМассив<ТипЭлемента>
```

ТипЭлемента: Тип элемента проекта. В результирующую коллекцию будут добавлены все элементы данного типа. Ограничения параметра типа: Стд::Отражение::ОтражениеЭлементаПроекта.

Полученная коллекция имеет

**Перегрузка** [ПолучитьВсе(ВидЭлемента: ВидЭлементаПроекта): ЧитаемыйМассив<ОтражениеЭлементаПроекта>](../../wiki/stdlib/projectelementsreflectioncollection-ru-189fccb75ec0.md)

---

### ПолучитьВсе

`Доступность: Сервер`

```
ПолучитьВсе(ВидЭлемента: ВидЭлементаПроекта): ЧитаемыйМассив<ОтражениеЭлементаПроекта>
```

Найти элементы проекта заданного вида, например, все справочники

**Перегрузка** [ПолучитьВсе<ТипЭлемента>(): ЧитаемыйМассив<ТипЭлемента>](../../wiki/stdlib/projectelementsreflectioncollection-ru-189fccb75ec0.md)

#### Примеры

Поиск всех справочников по виду элемента

```xbsl
метод ОбработатьВсеСправочникиПодсистемы(Подсистема: ОтражениеПодсистемыПроекта, Действие: (ОтражениеОбъектнойСущности) -> ничто)
    знч ВсеЭлементы = Подсистема.Элементы.ПолучитьВсе(ВидЭлементаПроекта.Справочник)
    для ОписаниеЭлемента из ВсеЭлементы
        знч ОписаниеСправочника = ОписаниеЭлемента как ОтражениеОбъектнойСущности
        // Выполняем переданное действие над справочником
        Действие(ОписаниеСправочника)
    ;
;
```

Поиск всех регистров по типу элемента

```xbsl
метод ОбработатьВсеРегистрыПодсистемы(Подсистема: ОтражениеПодсистемыПроекта, Действие: (ОтражениеСущностиРегистра) -> ничто)
    знч ВсеРегистры = Подсистема.Элементы.ПолучитьВсе<ОтражениеСущностиРегистра>()
    для ОписаниеРегистра из ВсеРегистры
        // Выполняем действие
        Действие(ОписаниеРегистра)
    ;
;
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

### ЧитаемаяКоллекция

[Единственный](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

[Размер](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

[Содержит](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)

[СодержитВсе](../../wiki/stdlib/readablecollection-ru-7f954f257c24.md)
