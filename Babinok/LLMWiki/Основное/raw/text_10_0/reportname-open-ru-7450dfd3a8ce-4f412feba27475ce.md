# {ИмяОтчета}.Открыть

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ReportName.Open_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ReportName.Open_ru/index.html
> SHA256: 3acdb3181356106589c9ac152abe73a10ba2f857c979425c5b1341b271735dbb
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяОтчета}.Открыть` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы отчета или панели отчетов.

Если у отчета не указана форма, при вызове будет открыта [ИмяОтчета.АвтоматическаяФорма](../../wiki/interface/reportname-automaticform-ru-2f8265fcddd0.md).

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

*Базовые типы:* [Команда](../../wiki/interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../../wiki/interface/usualcommand-ru-43da648bf5af.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяОтчета}.АвтоматическаяФорма
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../../wiki/interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](../../wiki/stdlib/reportname-open-ru-7450dfd3a8ce.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Видимость](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Доступность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../../wiki/interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../../wiki/interface/usualcommand-ru-43da648bf5af.md), [Представление](../../wiki/interface/usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Видимость](../../wiki/interface/command-ru-ad3bc8ea1407.md), [Доступность](../../wiki/interface/command-ru-ad3bc8ea1407.md), [ОпасностьДействия](../../wiki/interface/command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](../../wiki/interface/usualcommand-ru-43da648bf5af.md), [Представление](../../wiki/interface/usualcommand-ru-43da648bf5af.md)
