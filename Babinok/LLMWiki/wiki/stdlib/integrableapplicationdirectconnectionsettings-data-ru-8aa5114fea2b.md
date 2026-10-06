# НастройкиПрямогоПодключенияИнтегрируемогоПриложения.Данные

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrableapplicationdirectconnectionsettings-data-ru-8aa5114fea2b-35f7d3395ad95207](../../raw/text-10.0/integrableapplicationdirectconnectionsettings-data-ru-8aa5114fea2b-35f7d3395ad95207.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / IntegrableApplications.

Имена для поиска: `НастройкиПрямогоПодключенияИнтегрируемогоПриложения.Данные`, `IntegrableApplicationDirectConnectionSettings.Data`, `Стд::ИнтегрируемыеПриложения::НастройкиПрямогоПодключенияИнтегрируемогоПриложения.Данные`, `Std::IntegrableApplications::IntegrableApplicationDirectConnectionSettings.Data`.

## Обзор

Настройки подключения к приложению.

## Документированный контракт и примеры

`Версия 10.0 и выше`

`Стд::ИнтегрируемыеПриложения::НастройкиПрямогоПодключенияИнтегрируемогоПриложения.Данные` `Доступность: Сервер`

Настройки подключения к приложению.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

---

## Свойства

### Адрес

`Доступность: Сервер` `ТолькоЧтение`

```
Адрес: Строка
```

Адрес подключения по которому доступно приложение

---

### ИдКлиента

`Доступность: Сервер` `ТолькоЧтение`

```
ИдКлиента: Строка
```

Идентификатор клиента с которым будет выполняться подключение к приложению.

---

### СекретКлиента

`Доступность: Сервер` `ТолькоЧтение`

```
СекретКлиента: СекретПриложения?
```

Секрет клиента с которым будет выполняться подключение к приложению.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md) [(Переопределение)](integrableapplicationdirectconnectionsettings-data-ru-8aa5114fea2b.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Стд::ИнтегрируемыеПриложения — Пространство имён XBSL: Std](integrableapplications-fb6cab06cdcb.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [НастройкиПрямогоПодключенияИнтегрируемогоПриложения.Данные](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrableApplications/IntegrableApplicationDirectConnectionSettings.Data_ru/).
