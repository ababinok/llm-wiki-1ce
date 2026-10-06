# НавигационнаяКоманда

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [navigationcommand-ru-8290d7424fc8-b55432bf0592339a](../../raw/text-10.0/navigationcommand-ru-8290d7424fc8-b55432bf0592339a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Interface / Commands.

Имена для поиска: `НавигационнаяКоманда`, `NavigationCommand`, `Стд::Интерфейс::Команды::НавигационнаяКоманда`, `Std::Interface::Commands::NavigationCommand`.

## Обзор

Навигационная команда.

## Документированный контракт и примеры

`Стд::Интерфейс::Команды::НавигационнаяКоманда` `Доступность: Клиент`

Навигационная команда. Результатом выполнения является открытая форма.

**Сравнение**

Ссылочное

Структурное сравнение.

## Иерархия типа

*Базовые типы:* [Команда](command-ru-ad3bc8ea1407.md), [Объект](../stdlib/object-ru-9e351f286699.md), [ОбычнаяКоманда](usualcommand-ru-43da648bf5af.md)

*Дочерние типы:* [ИмяДокумента.ОткрытьСписок](../data/documentname-openlist-ru-eeda0f798e2f.md), [ИмяДокумента.СоздатьОбъект](../data/documentname-createobject-ru-edf1ad9b1831.md), [ИмяЖурналаДанных.ОткрытьСписок](../stdlib/datajournalname-openlist-ru-cb746a30d312.md), [ИмяИнтегрируемогоПриложения.ОткрытьСписок](../stdlib/integrableapplicationname-openlist-ru-cf5b5e36e7e8.md), [ИмяИнтегрируемогоПриложения.СоздатьОбъект](../stdlib/integrableapplicationname-createobject-ru-29d00b9c7a18.md), [ИмяКомандыНавигации](../stdlib/navigationcommandname-ru-e011f34476ce.md), [ИмяНабораКонстант.ОткрытьСписок](../stdlib/constantssetname-openlist-ru-9af058cb6e2e.md), [ИмяНабораКонстант.СоздатьОбъект](../stdlib/constantssetname-createobject-ru-2a9153249994.md), [ИмяНеПериодическогоНабораКонстант.ОткрытьОбъект](../stdlib/nonperiodicconstantssetname-openobject-ru-e3880953b129.md), [ИмяОбработки.Открыть](../stdlib/processingname-open-ru-d9588a5154bc.md), [ИмяОтчета.Открыть](../stdlib/reportname-open-ru-7450dfd3a8ce.md), [ИмяПанелиОтчетов.Открыть](../stdlib/reportpanelname-open-ru-10d8d67aecf8.md), [ИмяПланаОбмена.ОткрытьСписок](../integration/exchangeplanname-openlist-ru-5169161f614c.md), [ИмяПланаОбмена.СоздатьОбъект](../integration/exchangeplanname-createobject-ru-ecae22871288.md), [ИмяПодчиненногоРегистраСведений.ОткрытьСписок](../data/subordinatedinformationregistername-openlist-ru-a20b90ba7114.md), [ИмяРегистраНакопления.ОткрытьСписок](../data/accumulationregistername-openlist-ru-89b6018d8b7f.md), [ИмяРегистраСведений.ОткрытьСписок](../data/informationregistername-openlist-ru-d5af0d432ae6.md), [ИмяРегистраСведений.СоздатьОбъект](../data/informationregistername-createobject-ru-3bd63e8333f5.md), [ИмяСправочника.ОткрытьСписок](../data/catalogname-openlist-ru-d8eee47a1d8c.md), [ИмяСправочника.СоздатьОбъект](../data/catalogname-createobject-ru-0547549d53a0.md), [ИмяХранилищаНастроек.ОткрытьСписок](../data/settingsstoragename-openlist-ru-c3bec24005a0.md), [ИмяХранилищаНастроек.СоздатьОбъект](../data/settingsstoragename-createobject-ru-5f6b2fe2d3f3.md), [НавигационнаяКомандаИнформационныеСистемы](navigationcommandinformationsystems-ru-abefad73a4bb.md), [НавигационнаяКомандаПроцессыИнтеграции](navigationcommandintegrationprocesses-ru-bbe38601de37.md), [СтандартноеХранилищеНастроек.ОткрытьСписок](../data/standardsettingsstorage-openlist-ru-8307e16e9c77.md), [СтандартноеХранилищеНастроек.СоздатьОбъект](../data/standardsettingsstorage-createobject-ru-76a8bb7aa0fd.md)

---

## Конструкторы

### НавигационнаяКоманда

`Версия 9.0 и выше`

`Доступность: Клиент`

```
НавигационнаяКоманда(
  Представление: Строка,
  Изображение: Url|ДвоичныйОбъект.Ссылка|? = Неопределено,
  ТипФормы: Тип<Форма<неизвестно>>, Важность: ВажностьКоманды = ВажностьКоманды.Обычная, Доступность: Булево = Истина, Видимость: Булево = Истина, ОпасностьДействия: ОпасностьДействия = ОпасностьДействия.Отсутствует)
```

Создает навигационную команду с заданными полями.

---

### НавигационнаяКоманда

`Версия 8.0 и ниже`

> **Исторический контракт:** верхняя граница версии 8.0; не используйте этот член для 10.0.


`Доступность: Клиент`

```
НавигационнаяКоманда(
  Представление: Строка,
  Изображение: ДвоичныйОбъект.Ссылка? = Неопределено,
  ТипФормы: Тип<Форма<неизвестно>>, Важность: ВажностьКоманды = ВажностьКоманды.Обычная, Доступность: Булево = Истина, Видимость: Булево = Истина, ОпасностьДействия: ОпасностьДействия = ОпасностьДействия.Отсутствует)
```

Конструктор удален.

---

## Методы

### ПолучитьФорму

`Доступность: Клиент`

```
ПолучитьФорму(): Форма<неизвестно>
```

Возвращает форму, которая была бы открыта в случае исполнения команды.

---

## Список унаследованных методов

### Команда

[Выполнить](command-ru-ad3bc8ea1407.md)

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

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Интерфейс::Команды — Пространство имён XBSL: Std / Interface](commands-04b6fdb9d9a8.md)
- [НавигационнаяКоманда — Настройки компонента](navigationcommand-ru-513a313bd128.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [НавигационнаяКоманда](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Commands/NavigationCommand_ru/).
