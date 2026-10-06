# УзлыСхемыИнтеграции

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/IntegrationSchemaNodes_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/IntegrationBus/IntegrationSchemaNodes_ru/index.html
> SHA256: b693997453d363b82825b0cc8598818f26dcb046305b17d236d491597dc4bcdd
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ИнтеграционнаяШина::УзлыСхемыИнтеграции` `Доступность: КлиентИСервер`

Узлы схемы процесса интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Обходимое<УзелСхемыИнтеграции>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИмяПроцессаИнтеграции.УзлыСхемы](../../wiki/integration/integrationprocessname-schemanodes-ru-d9c29bc29c7b.md)

---

## Примеры

**Общие примеры**

Пример обработчика для узла типа [МаршрутизаторПоСодержимому](../../wiki/integration/integrationschemanodekind-ru-a40f2abdcc09.md) процесса интеграции с именем `СетьМагазинов`, в котором следующий узел определяется в зависимости от значения параметра сообщения.

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
