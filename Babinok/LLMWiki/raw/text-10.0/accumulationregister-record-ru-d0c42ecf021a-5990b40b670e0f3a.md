# РегистрНакопления.Запись

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccumulationRegisters/AccumulationRegister.Record_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccumulationRegisters/AccumulationRegister.Record_ru/index.html
> SHA256: 20961b726e8872096705e9799104c9ced82be36cbf63eddea50f0789d0b2f251
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::РегистрыНакопления::РегистрНакопления.Запись` `Доступность: КлиентИСервер`

Базовый тип для всех записей регистров накопления.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Сущность.Запись](../../wiki/data/entity-record-ru-aff87f027f11.md), [Сущность.ЗаписьПодчиненнаяРегистратору](../../wiki/data/entity-recordersubordinatedrecord-ru-7eff8574ef41.md)

*Дочерние типы:* [ИмяРегистраНакопления.Запись](../../wiki/data/accumulationregistername-record-ru-e8eb9213772a.md)

---

## Свойства

### КлючОсновногоФильтра

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
КлючОсновногоФильтра: РегистрНакопления.КлючОсновногоФильтра
```

Структура содержащая единственное свойство `Регистратор`. Используется для регистрации изменений механизмом обмена данными.

---

### Регистратор

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Регистратор: Документ.Ссылка?
```

Ссылка на документ-регистратор, которому подчинена запись.

Переопределение: [Регистратор](../../wiki/data/accumulationregister-record-ru-d0c42ecf021a.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Сущность.ЗаписьПодчиненнаяРегистратору

[Активность](../../wiki/data/entity-recordersubordinatedrecord-ru-7eff8574ef41.md)
