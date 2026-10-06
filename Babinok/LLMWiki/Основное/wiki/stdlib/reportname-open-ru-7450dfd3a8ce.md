# {ИмяОтчета}.Открыть

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [reportname-open-ru-7450dfd3a8ce-4f412feba27475ce](../../raw/text-10.0/reportname-open-ru-7450dfd3a8ce-4f412feba27475ce.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: ReportName.

Имена для поиска: `{ИмяОтчета}.Открыть`, `ReportName.Open`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяОтчета}.Открыть`, `DeveloperName::ProjectName::SubsystemName::ReportName.Open`.

## Обзор

Команда открытия формы отчета или панели отчетов.

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяОтчета}.Открыть` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы отчета или панели отчетов.

Если у отчета не указана форма, при вызове будет открыта [ИмяОтчета.АвтоматическаяФорма](../interface/reportname-automaticform-ru-2f8265fcddd0.md).

```yaml
ВидЭлемента: ФрагментКомандногоИнтерфейса
Ид: 2b34b13b-0f4d-43cc-b209-ae47c943f457
Имя: КомандыОтчетов
ОбластьВидимости: ВПодсистеме
Элементы:
  - =Отчет1.Открыть
  - =Отчет2.Открыть
  - =Отчет3.Открыть
  - =Отчеты.ОткрытьАнализДанных
```

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../interface/navigationcommand-ru-8290d7424fc8.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [ОбычнаяКоманда](../interface/usualcommand-ru-43da648bf5af.md), [Одиночка](singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяОтчета}.АвтоматическаяФорма
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](reportname-open-ru-7450dfd3a8ce.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../interface/usualcommand-ru-43da648bf5af.md), [Представление](../interface/usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](../interface/command-ru-ad3bc8ea1407.md), [Видимость](../interface/command-ru-ad3bc8ea1407.md), [Доступность](../interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../interface/usualcommand-ru-43da648bf5af.md), [Представление](../interface/usualcommand-ru-43da648bf5af.md)

## See Also

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [Отчет — Элемент проекта](../project/report-76b54cc6c05b.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяОтчета}.Открыть](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ReportName.Open_ru/).
