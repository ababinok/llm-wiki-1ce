# {ИмяПроцессаИнтеграции}.УзлыСхемы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.SchemaNodes_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.SchemaNodes_ru/index.html
> SHA256: e740175801ffd0b9ace0bef7adf890c80c708722b3c6e3378c75cee38fe6301b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.УзлыСхемы` `Доступность: КлиентИСервер`

Узлы схемы процесса интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Обходимое<УзелСхемыИнтеграции>](../../wiki/stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [УзлыСхемыИнтеграции](../../wiki/integration/integrationschemanodes-ru-404c8474f725.md)

---

## Свойства

### ИмяУзлаНазначениеПроцессаИнтеграции

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ИмяУзлаНазначениеПроцессаИнтеграции: УзелСхемыИнтеграции
```

---

### {ИмяУзлаСхемы}

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ИмяУзлаСхемы: УзелСхемыИнтеграции
```

Для каждого узла схемы создается свойство с именем узла.

#### Примеры

Пример обработчика для отправки сообщения в процесс интеграции с именем `СетьМагазинов`, в котором следующий узел определяется в зависимости от значения параметра сообщения.

```xbsl
метод ОтправитьСообщение(Запрос: HttpСервисЗапрос)
    знч ЯвляетсяАрхивом = Запрос.Заголовки.ПолучитьПервый("content-type") == "application/zip"
    знч Сообщение = новый СообщениеИнтеграции({"IsArchive":ЯвляетсяАрхивом}, Запрос.Тело)
    СетьМагазинов.ОтправитьСообщениеВУзлы(Сообщение, СетьМагазинов.Схема.Узлы.ОтПартнеров)
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

### УзлыСхемыИнтеграции

[КакСоответствие](../../wiki/integration/integrationschemanodes-ru-404c8474f725.md)
