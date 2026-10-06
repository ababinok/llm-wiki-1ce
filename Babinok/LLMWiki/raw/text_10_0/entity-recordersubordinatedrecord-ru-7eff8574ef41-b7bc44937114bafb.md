# Сущность.ЗаписьПодчиненнаяРегистратору

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Entities/Entity.RecorderSubordinatedRecord_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Entities/Entity.RecorderSubordinatedRecord_ru/index.html
> SHA256: 82c61ed19ab7781c30fc60f517cdfb218cfe9e5d1254a9484ad365b9cc359147
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Сущности::Сущность.ЗаписьПодчиненнаяРегистратору` `Доступность: КлиентИСервер`

Базовый тип для записей необъектных сущностей подчинённых сущности-регистратору.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Сущность.Запись](../../wiki/data/entity-record-ru-aff87f027f11.md)

*Дочерние типы:* [ИмяПодчиненногоРегистраСведений.Запись](../../wiki/data/subordinatedinformationregistername-record-ru-5f5d606d63e0.md), [РегистрНакопления.Запись](../../wiki/data/accumulationregister-record-ru-d0c42ecf021a.md)

---

## Свойства

### Активность

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Активность: Булево
```

Содержит признак, определяющий влияние записи на итоги регистра. Если значение Ложь, то запись не учитывается в итогах регистра.

---

### Регистратор

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Регистратор: Сущность.Ключ?
```

Ссылка на сущность-регистратор, которой подчинена запись.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
