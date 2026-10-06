# НастройкиТайловогоСервераГеографическойКарты

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/GeographicMaps/GeographicMapTileServerSettings_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/GeographicMaps/GeographicMapTileServerSettings_ru/index.html
> SHA256: 0958f18d53c77709771ebaec0cfc24b78b4dec42589f6f09e8128e126468d69a
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ГеографическиеКарты::НастройкиТайловогоСервераГеографическойКарты` `Доступность: КлиентИСервер`

Структура, в которой задаются настройки тайлового сервера, откуда географическая карта будет брать базовый слой.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

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

[НастройкиТайловогоСервераГеографическойКарты](../../wiki/stdlib/geographicmaptileserversettings-ru-fa8b4479ab53.md)

со значениями свойств, соответствующими параметрам конструктора.

---

## Свойства

### КлючApi

`Доступность: КлиентИСервер`

```
КлючApi: Строка?
```

API-ключ тайлового сервера, если необходим. Можно указывать только в [ШаблонUrl](../../wiki/stdlib/geographicmaptileserversettings-ru-fa8b4479ab53.md).

---

### Поставщик

`Доступность: КлиентИСервер`

```
Поставщик: Авто|ПоставщикГеографическихКарт
```

Используемый поставщик API тайлового сервера. Для [Произвольный](../../wiki/stdlib/geographicmapsprovider-ru-442e16f070f5.md), [OpenStreetMap](../../wiki/stdlib/geographicmapsprovider-ru-442e16f070f5.md) и [Авто](../../wiki/stdlib/auto-ru-1b14ed166f8e.md) требуется указание адреса.

Если [Авто](../../wiki/stdlib/auto-ru-1b14ed166f8e.md), поставщик определяется на основании URL: если URL начинается с "[https://tiles.api-maps.yandex.ru](https://tiles.api-maps.yandex.ru)", то [ЯндексКарты](../../wiki/stdlib/geographicmapsprovider-ru-442e16f070f5.md), если с "[https://tile.openstreetmap.org](https://tile.openstreetmap.org)", то [OpenStreetMap](../../wiki/stdlib/geographicmapsprovider-ru-442e16f070f5.md), иначе [Произвольный](../../wiki/stdlib/geographicmapsprovider-ru-442e16f070f5.md).

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

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/stdlib/geographicmaptileserversettings-ru-fa8b4479ab53.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
