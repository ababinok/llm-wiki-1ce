# {ИмяОбработки}.Открыть

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ProcessingName.Open_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ProcessingName.Open_ru/index.html
> SHA256: 2b91536bdd48f7e6adcf7eef2970fa3fe178f3314c925f4f1e871aa243d788b4
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 8.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяОбработки}.Открыть` `Тип-одиночка` `Доступность: Клиент`

Команда открытия формы обработки Если у обработки не указана форма, при вызове будет открыта [ИмяОбработки.АвтоматическаяФорма](../../wiki/interface/processingname-automaticform-ru-40572408be14.md).

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../../wiki/interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../../wiki/interface/usualcommand-ru-43da648bf5af.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### Выполнить

`Версия 10.0 и выше`

`Доступность: Клиент`

```
Выполнить()
```

Выполняет открытие формы обработки.

---

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): {ИмяОбработки}.АвтоматическаяФорма
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../../wiki/interface/command-ru-ad3bc8ea1407.md) [(Переопределение)](../../wiki/stdlib/processingname-open-ru-d9588a5154bc.md)

### НавигационнаяКоманда

[ПолучитьФорму](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](../../wiki/stdlib/processingname-open-ru-d9588a5154bc.md)

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
