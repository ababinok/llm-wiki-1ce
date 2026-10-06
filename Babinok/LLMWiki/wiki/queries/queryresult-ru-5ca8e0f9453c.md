# РезультатЗапроса

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [queryresult-ru-5ca8e0f9453c-2edc2786dce6aed4](../../raw/text-10.0/queryresult-ru-5ca8e0f9453c-2edc2786dce6aed4.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Database.

Имена для поиска: `РезультатЗапроса`, `QueryResult`, `Стд::БазаДанных::РезультатЗапроса<ТипСтрокиРезультатаЗапроса>`, `Std::Database::QueryResult`.

## Обзор

ТипСтрокиРезультатаЗапроса: тип строки результата.

## Документированный контракт и примеры

`Стд::БазаДанных::РезультатЗапроса<ТипСтрокиРезультатаЗапроса>` `Доступность: Сервер`

ТипСтрокиРезультатаЗапроса: тип строки результата.

Предназначен для работы с результатом запроса на языке запросов. После полного обхода (получении последней строки результата или если результатов вообще нет) автоматически освобождает внутренние ресурсы и не требует явного закрытия. Обход возможен только один раз.

**Сравнение**

Ссылочное

**Обход в цикле**

Тип: QueryResultRowType

## Иерархия типа

*Базовые типы:* [Закрываемое](../stdlib/closeable-ru-67cd73fca69d.md), [Обходимое<ТипСтрокиРезультатаЗапроса>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Методы

### Закрыть

`Доступность: Сервер`

```
Закрыть()
```

**Переопределение** [Закрываемое::Закрыть](../stdlib/closeable-ru-67cd73fca69d.md)

---

### ПолучитьОписанияКолонок

`Доступность: Сервер`

```
ПолучитьОписанияКолонок(): ЧитаемыйМассив<ОписаниеКолонкиРезультатаЗапроса>
```

Возвращает описания колонок результата запроса.

---

## Список унаследованных методов

### Закрываемое

[Закрыть](../stdlib/closeable-ru-67cd73fca69d.md) [(Переопределение)](queryresult-ru-5ca8e0f9453c.md)

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

[Пусто](../stdlib/iterable-ru-283adb0cc9eb.md)

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

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../data/overview.md)
- [Стд::БазаДанных — Пространство имён XBSL: Std](../data/database-c7a95b8f6198.md)
- [Хранимые данные и порождаемые типы](../data/entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](../data/object-form-and-crud.md)

Оригинал: [РезультатЗапроса](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Database/QueryResult_ru/).
