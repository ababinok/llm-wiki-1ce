# НавигационнаяКомандаИнформационныеСистемы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Interface/NavigationCommandInformationSystems_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/IntegrationBus/Interface/NavigationCommandInformationSystems_ru/index.html
> SHA256: fedb4b3249e0744d8de74687511d7ede9d8fc4b37277373f95bc4226f6b61b38
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 7.0 и выше`

`Стд::ИнтеграционнаяШина::Интерфейс::НавигационнаяКомандаИнформационныеСистемы` `Тип-одиночка` `Доступность: Клиент`

Навигационная команда для открытия окна информационных систем во встроенном интерфейсе 1С:Шина.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](../../wiki/interface/command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](../../wiki/interface/usualcommand-ru-43da648bf5af.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Примеры

**Общие примеры**

Пример фрагмента командного интерфейса, включающего навигационную команду для открытия окна информационных систем, во встроенном интерфейсе 1С:Шина.

```yaml
ВидЭлемента: ФрагментКомандногоИнтерфейса
Ид: 3f538391-d1d8-4b45-8b23-842c8d760284
ОбластьВидимости: ВПодсистеме
Имя: ОсновнаяНавигация
Элементы:
  -
    =Стд::ИнтеграционнаяШина::Интерфейс::НавигационнаяКомандаПроцессыИнтеграции
  -
    =Стд::ИнтеграционнаяШина::Интерфейс::НавигационнаяКомандаИнформационныеСистемы
```

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): InformationSystemsListForm
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](../../wiki/interface/command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](../../wiki/interface/navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](../../wiki/interface/navigationcommandinformationsystems-ru-abefad73a4bb.md)

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
