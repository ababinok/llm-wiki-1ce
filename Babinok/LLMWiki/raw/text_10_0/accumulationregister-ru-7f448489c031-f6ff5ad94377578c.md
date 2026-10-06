# РегистрНакопления

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccumulationRegisters/AccumulationRegister_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccumulationRegisters/AccumulationRegister_ru/index.html
> SHA256: 33af6a2edd14d8a459d8ca9d30aed4ca2ba7f8504bda24879dd2a14892a74523
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::РегистрыНакопления::РегистрНакопления` `Доступность: КлиентИСервер`

Базовый тип для всех менеджеров регистров накопления.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

*Дочерние типы:* [ИмяРегистраНакопления](../../wiki/data/accumulationregistername-ru-ca3f7a553094.md)

---

## Методы

### ПересчитатьРазрешенияДоступа

`Доступность: Сервер`

```
ПересчитатьРазрешенияДоступа()
```

Пересчитывает разрешения доступа для регистра накопления.

#### Примеры

```xbsl
ЗаказыКлиентов.ПересчитатьРазрешенияДоступа()
```

---

### ПересчитатьРазрешенияДоступаДляОбъектов

`Доступность: Сервер`

```
ПересчитатьРазрешенияДоступаДляОбъектов()
```

Пересчитывает разрешения доступа для всех записей регистра накопления.

#### Примеры

```xbsl
ЗаказыКлиентов.ПересчитатьРазрешенияДоступаДляОбъектов()
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
