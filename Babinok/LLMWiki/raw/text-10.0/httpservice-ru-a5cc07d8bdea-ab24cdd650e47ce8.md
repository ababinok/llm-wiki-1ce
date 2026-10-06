# HttpСервис

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HttpServices/HttpService_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/HttpServices/HttpService_ru/index.html
> SHA256: f7199017fc411cf5dad2a675e2deab9553aa8c57fc52aa4af1ae47deea305154
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::HttpСервисы::HttpСервис` `Доступность: Сервер`

Базовый тип Http-сервисов.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

---

## Методы

### ПересчитатьРазрешенияДоступа

`Доступность: Сервер`

```
ПересчитатьРазрешенияДоступа()
```

Пересчитывает разрешения доступа для Http-сервиса.

#### Примеры

В примере пересчитываются разрешения доступа для всех Http-сервисов приложения.

```xbsl
для Сервис из HttpСервисы
    Сервис.ПересчитатьРазрешенияДоступа()
;
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
