# РегистрНакопления.КлючОсновногоФильтра

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccumulationRegisters/AccumulationRegister.MainFilterKey_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccumulationRegisters/AccumulationRegister.MainFilterKey_ru/index.html
> SHA256: ade1f3d95e76d31763c0f9ea0bc918d07c0b3964d69c6189c6ff05e8f94f8e61
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::РегистрыНакопления::РегистрНакопления.КлючОсновногоФильтра` `Доступность: КлиентИСервер`

Структура описывающая ключ основного фильтра регистра накопления (содержит единственное свойство `Регистратор`). Используется механизмом обмена данными для регистрации изменений записей регистра накопления. Предоставляется как поле, в таблице регистра накопления и таблице изменений данных регистра накопления.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИмяРегистраНакопления.КлючОсновногоФильтра](../../wiki/data/accumulationregistername-mainfilterkey-ru-fb566c677c70.md)

---

## Свойства

### Регистратор

`Доступность: Сервер` `ТолькоЧтение`

```
Регистратор: Документ.Ссылка?
```

Ссылка на документ-регистратор по которой выполняется фильтр записей.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
