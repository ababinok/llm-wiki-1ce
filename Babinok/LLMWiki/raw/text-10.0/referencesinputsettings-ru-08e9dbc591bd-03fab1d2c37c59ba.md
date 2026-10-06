# НастройкиВводаСсылок

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/DataInput/ReferencesInputSettings_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/DataInput/ReferencesInputSettings_ru/index.html
> SHA256: d1fb2e10679057a541fbaaa7d31cd5f8fece331673740c48aa9807ae367b8c8e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ВводДанных::НастройкиВводаСсылок` `Доступность: КлиентИСервер`

Содержит настройки ввода ссылочных значений в [ПолеВвода](../../wiki/interface/edit-ru-cde85140b31e.md).

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### НастройкиВводаСсылок

`Доступность: КлиентИСервер`

```
НастройкиВводаСсылок(НастройкиПоТипу: Соответствие<Тип<Сущность.Ключ>, НастройкиВводаСсылки>)
```

Создает пустой объект

[НастройкиВводаСсылок](../../wiki/interface/referencesinputsettings-ru-08e9dbc591bd.md)

.

---

## Свойства

### НастройкиПоТипу

`Доступность: КлиентИСервер`

```
НастройкиПоТипу: Соответствие<Тип<Сущность.Ключ>, НастройкиВводаСсылки>
```

Содержит отдельные настройки ввода для каждого редактируемого ссылочного типа.

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

Строковое представление объекта.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/interface/referencesinputsettings-ru-08e9dbc591bd.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
