# УзлыСхемыИнтеграции

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationschemanodes-ru-404c8474f725-37d3792f27516236](../../raw/text-10.0/integrationschemanodes-ru-404c8474f725-37d3792f27516236.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / IntegrationBus.

Имена для поиска: `УзлыСхемыИнтеграции`, `IntegrationSchemaNodes`, `Стд::ИнтеграционнаяШина::УзлыСхемыИнтеграции`, `Std::IntegrationBus::IntegrationSchemaNodes`.

## Обзор

*Базовые типы:* [Обходимое<УзелСхемыИнтеграции>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::ИнтеграционнаяШина::УзлыСхемыИнтеграции` `Доступность: КлиентИСервер`

Узлы схемы процесса интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Обходимое<УзелСхемыИнтеграции>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИмяПроцессаИнтеграции.УзлыСхемы](integrationprocessname-schemanodes-ru-d9c29bc29c7b.md)

---

## Примеры

**Общие примеры**

Пример обработчика для узла типа [МаршрутизаторПоСодержимому](integrationschemanodekind-ru-a40f2abdcc09.md) процесса интеграции с именем `СетьМагазинов`, в котором следующий узел определяется в зависимости от значения параметра сообщения.

```xbsl
метод СтатусОпросаВитрины(Контекст: КонтекстВызоваИнтеграции, Сообщение: СетьМагазинов.Сообщение): Коллекция<УзелСхемыИнтеграции>
    если Сообщение.КодОтветаHttp == 200
        возврат [Схема.Узлы.ОтВитрины]
    ;
    возврат [Схема.Узлы.ПротоколОшибок]
;
```

---

## Методы

### КакСоответствие

`Доступность: КлиентИСервер`

```
КакСоответствие(): ЧитаемоеСоответствие<Строка, УзелСхемыИнтеграции>
```

Возвращает узлы схемы процесса интеграции в виде соответствия имя узла - узел.

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

- [Навигатор раздела](overview.md)
- [Стд::ИнтеграционнаяШина — Пространство имён XBSL: Std](integrationbus-47a88b720322.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [УзлыСхемыИнтеграции](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/IntegrationSchemaNodes_ru/).
