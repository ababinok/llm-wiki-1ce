# ХранилищеНастроек.Объект

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/SettingsStorages/SettingsStorage.Object_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/SettingsStorages/SettingsStorage.Object_ru/index.html
> SHA256: a7be9c2d8a86653f169d09ec119ee302b4fb72ba6d2bde8b8bb2ea717c3f6cc9
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ХранилищаНастроек::ХранилищеНастроек.Объект` `Доступность: КлиентИСервер`

Базовый тип для объектов хранилища настроек. Содержит общие для всех объектов хранилищ свойства и методы.

**Сравнение**

Ссылочное

Сравнение по ссылке.

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [Сущность.Объект](../../wiki/data/entity-object-ru-6a8abb73357f.md)

*Дочерние типы:* [ИмяХранилищаНастроек.Объект](../../wiki/data/settingsstoragename-object-ru-76dd064bfbbf.md), [СтандартноеХранилищеНастроек.Объект](../../wiki/data/standardsettingsstorage-object-ru-cca7b461551d.md)

---

## Свойства

### МеткаВерсии

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
МеткаВерсии: Ууид
```

Случайный Ууид, изменяющийся каждый раз при записи объекта. Используется в механизме оптимистических блокировок.

---

### Ссылка

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Ссылка: ХранилищеНастроек.Ссылка
```

Ссылка

Переопределение: [Ссылка](../../wiki/data/settingsstorage-object-ru-0ed39bf10f11.md)

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

### ЭтоНовый

`Доступность: КлиентИСервер`

```
ЭтоНовый(): Булево
```

Признак того, что объект только что создан и не был еще записан.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/data/settingsstorage-object-ru-0ed39bf10f11.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Представляемое

[Представление](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)
