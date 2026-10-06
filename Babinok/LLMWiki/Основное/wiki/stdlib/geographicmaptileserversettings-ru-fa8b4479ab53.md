# НастройкиТайловогоСервераГеографическойКарты

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [geographicmaptileserversettings-ru-fa8b4479ab53-d1b9d05e4363d216](../../raw/text_10_0/geographicmaptileserversettings-ru-fa8b4479ab53-d1b9d05e4363d216.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / GeographicMaps.

Имена для поиска: `НастройкиТайловогоСервераГеографическойКарты`, `GeographicMapTileServerSettings`, `Стд::ГеографическиеКарты::НастройкиТайловогоСервераГеографическойКарты`, `Std::GeographicMaps::GeographicMapTileServerSettings`.

## Обзор

Структура, в которой задаются настройки тайлового сервера, откуда географическая карта будет брать базовый слой.

## Документированный контракт и примеры

`Стд::ГеографическиеКарты::НастройкиТайловогоСервераГеографическойКарты` `Доступность: КлиентИСервер`

Структура, в которой задаются настройки тайлового сервера, откуда географическая карта будет брать базовый слой.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md)

---

## Конструкторы

### НастройкиТайловогоСервераГеографическойКарты

`Доступность: КлиентИСервер`

```
НастройкиТайловогоСервераГеографическойКарты(
  Поставщик: Авто|ПоставщикГеографическихКарт,
  ШаблонUrl: Строка,
  КлючApi: Строка?)
```

Создает объект

[НастройкиТайловогоСервераГеографическойКарты](geographicmaptileserversettings-ru-fa8b4479ab53.md)

со значениями свойств, соответствующими параметрам конструктора.

---

## Свойства

### КлючApi

`Доступность: КлиентИСервер`

```
КлючApi: Строка?
```

API-ключ тайлового сервера, если необходим. Можно указывать только в [ШаблонUrl](geographicmaptileserversettings-ru-fa8b4479ab53.md).

---

### Поставщик

`Доступность: КлиентИСервер`

```
Поставщик: Авто|ПоставщикГеографическихКарт
```

Используемый поставщик API тайлового сервера. Для [Произвольный](geographicmapsprovider-ru-442e16f070f5.md), [OpenStreetMap](geographicmapsprovider-ru-442e16f070f5.md) и [Авто](auto-ru-1b14ed166f8e.md) требуется указание адреса.

Если [Авто](auto-ru-1b14ed166f8e.md), поставщик определяется на основании URL: если URL начинается с "[https://tiles.api-maps.yandex.ru](https://tiles.api-maps.yandex.ru)", то [ЯндексКарты](geographicmapsprovider-ru-442e16f070f5.md), если с "[https://tile.openstreetmap.org](https://tile.openstreetmap.org)", то [OpenStreetMap](geographicmapsprovider-ru-442e16f070f5.md), иначе [Произвольный](geographicmapsprovider-ru-442e16f070f5.md).

---

### ШаблонUrl

`Доступность: КлиентИСервер`

```
ШаблонUrl: Строка
```

Шаблон URL-адреса тайлового сервера для использования. Обязательно должен быть задан.

Формат: "https://{s}.somedomain.com/suburl/{z}/{x}/{y}{r}.png", где s — субдомен, если поддерживается, x, y, z — координаты, r — добавляет '@2x' в URL для тайлов для Retina, если поддерживается.

Пример значения свойства для тайлов Яндекс Карт: "[https://tiles.api-maps.yandex.ru/v1/tiles/?apikey=YOUR_API_KEY⟨=ru_RU&x=\{x\}&y=\{y\}&z=\{z\}&l=map](https://tiles.api-maps.yandex.ru/v1/tiles/?apikey=YOUR_API_KEY&lang=ru_RU&x=%5C%7Bx%5C%7D&y=%5C%7By%5C%7D&z=%5C%7Bz%5C%7D&l=map)".

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление объекта.

**Переопределение** [Объект::ВСтроку](object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md) [(Переопределение)](geographicmaptileserversettings-ru-fa8b4479ab53.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../interface/overview.md)
- [Стд::ГеографическиеКарты — Пространство имён XBSL: Std](geographicmaps-e9b51cd385de.md)
- [Тип компонента, экземпляр и наследование](../interface/component-model.md)
- [Выбор компонентов для формы](../interface/component-choice.md)
- [Вычисляемые свойства и связи интерфейса](../interface/computed-properties-and-bindings.md)
- [События компонентов и обработчики](../interface/events-and-handlers.md)
- [Маршрут: таблица и динамический список](../interface/table-and-dynamic-list.md)

Оригинал: [НастройкиТайловогоСервераГеографическойКарты](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/GeographicMaps/GeographicMapTileServerSettings_ru/).
