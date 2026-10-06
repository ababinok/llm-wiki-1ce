# НавигационнаяКомандаПроцессыИнтеграции

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [navigationcommandintegrationprocesses-ru-bbe38601de37-f89c8f0ce4906643](../../raw/text-10.0/navigationcommandintegrationprocesses-ru-bbe38601de37-f89c8f0ce4906643.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / IntegrationBus / Interface.

Имена для поиска: `НавигационнаяКомандаПроцессыИнтеграции`, `NavigationCommandIntegrationProcesses`, `Стд::ИнтеграционнаяШина::Интерфейс::НавигационнаяКомандаПроцессыИнтеграции`, `Std::IntegrationBus::Interface::NavigationCommandIntegrationProcesses`.

## Обзор

Навигационная команда для открытия окна процессов интеграции во встроенном интерфейсе 1С:Шина.

## Документированный контракт и примеры

`Версия 7.0 и выше`

`Стд::ИнтеграционнаяШина::Интерфейс::НавигационнаяКомандаПроцессыИнтеграции` `Тип-одиночка` `Доступность: Клиент`

Навигационная команда для открытия окна процессов интеграции во встроенном интерфейсе 1С:Шина.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Команда](command-ru-ad3bc8ea1407.md), [НавигационнаяКоманда](navigationcommand-ru-8290d7424fc8.md), [Объект](../stdlib/object-ru-9e351f286699.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](usualcommand-ru-43da648bf5af.md), [Одиночка](../stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Примеры

**Общие примеры**

Пример фрагмента командного интерфейса, включающего навигационную команду для открытия окна процессов интеграции, во встроенном интерфейсе 1С:Шина.

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
ПолучитьФорму(): EsbForm
```

**Переопределение** [НавигационнаяКоманда::ПолучитьФорму](navigationcommand-ru-8290d7424fc8.md)

---

## Список унаследованных методов

### Команда

[Выполнить](command-ru-ad3bc8ea1407.md)

### НавигационнаяКоманда

[ПолучитьФорму](navigationcommand-ru-8290d7424fc8.md) [(Переопределение)](navigationcommandintegrationprocesses-ru-bbe38601de37.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Команда

[Важность](command-ru-ad3bc8ea1407.md), [Видимость](command-ru-ad3bc8ea1407.md), [Доступность](command-ru-ad3bc8ea1407.md), [ОпасностьДействия](command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](usualcommand-ru-43da648bf5af.md), [Представление](usualcommand-ru-43da648bf5af.md)

## Список унаследованных событий

### Команда

[Важность](command-ru-ad3bc8ea1407.md), [Видимость](command-ru-ad3bc8ea1407.md), [Доступность](command-ru-ad3bc8ea1407.md), [ОпасностьДействия](command-ru-ad3bc8ea1407.md)

### ОбычнаяКоманда

[Изображение](usualcommand-ru-43da648bf5af.md), [Представление](usualcommand-ru-43da648bf5af.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Стд::ИнтеграционнаяШина::Интерфейс — Пространство имён XBSL: Std / IntegrationBus](interface-12a394773b39.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [НавигационнаяКомандаПроцессыИнтеграции](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Interface/NavigationCommandIntegrationProcesses_ru/).
