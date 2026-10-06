# {ИмяПроцессаИнтеграции}.УзлыПути

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationprocessname-pathnodes-ru-1856c9440cc1-f79b87791a341b98](../../raw/text-10.0/integrationprocessname-pathnodes-ru-1856c9440cc1-f79b87791a341b98.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: IntegrationProcessName.

Имена для поиска: `{ИмяПроцессаИнтеграции}.УзлыПути`, `IntegrationProcessName.PathNodes`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.УзлыПути`, `DeveloperName::ProjectName::SubsystemName::IntegrationProcessName.PathNodes`.

## Обзор

Информация о следовании сообщения от первого узла схемы до текущего узла схемы.

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.УзлыПути` `Доступность: Сервер`

Информация о следовании сообщения от первого узла схемы до текущего узла схемы.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Обходимое<ИмяПроцессаИнтеграции.УзелПути>](../stdlib/iterable-ru-283adb0cc9eb.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Свойства

### Источник

`Доступность: Сервер` `ТолькоЧтение`

```
Источник: {ИмяПроцессаИнтеграции}.УзелПути
```

Первый узел пути (источник) в пути следования сообщения.

---

### Текущий

`Доступность: Сервер` `ТолькоЧтение`

```
Текущий: {ИмяПроцессаИнтеграции}.УзелПути
```

Текущий узел пути в пути следования сообщения.

---

## Методы

### Получить

`Доступность: Сервер`

```
Получить(Узел: УзелСхемыИнтеграции): {ИмяПроцессаИнтеграции}.УзелПути?
```

Возвращает узел пути по узлу схемы

`Узел`

или

`Неопределено`

, если сообщение не проходило через указанный в параметре

`Узел`

узел схемы.

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

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяПроцессаИнтеграции}.УзлыПути](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.PathNodes_ru/).
