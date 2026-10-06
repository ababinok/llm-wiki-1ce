# РегистрСведений

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/InformationRegisters/InformationRegister_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/InformationRegisters/InformationRegister_ru/index.html
> SHA256: d22c809b2fd78c75318e5e912a6ce2881e48ed3853988478b606f897d538c693
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::РегистрыСведений::РегистрСведений` `Доступность: КлиентИСервер`

Базовый тип для всех менеджеров регистров сведений.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

*Дочерние типы:* [ИмяПодчиненногоРегистраСведений](../../wiki/data/subordinatedinformationregistername-ru-fcbbd736eae6.md), [ИмяРегистраСведений](../../wiki/data/informationregistername-ru-a758d6e52059.md)

---

## Методы

### ПересчитатьРазрешенияДоступа

`Доступность: Сервер`

```
ПересчитатьРазрешенияДоступа()
```

Пересчитывает разрешения доступа для регистра сведений.

#### Примеры

```xbsl
ЦеныТоваров.ПересчитатьРазрешенияДоступа()
```

---

### ПересчитатьРазрешенияДоступаДляОбъектов

`Доступность: Сервер`

```
ПересчитатьРазрешенияДоступаДляОбъектов()
```

Пересчитывает разрешения доступа для всех записей регистра сведений.

#### Примеры

```xbsl
ЦеныТоваров.ПересчитатьРазрешенияДоступаДляОбъектов()
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
