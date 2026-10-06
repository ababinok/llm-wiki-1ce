# НаборКонстант.Запись

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/ConstantsSets/ConstantsSet.Record_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/ConstantsSets/ConstantsSet.Record_ru/index.html
> SHA256: a69c2ff2e8c4b288f7a41eee3ec133d2093540485d6d1338c244eeeb1bc0e681
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::НаборыКонстант::НаборКонстант.Запись` `Доступность: КлиентИСервер`

Базовый тип для всех записей наборов констант.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Сущность.Запись](../../wiki/data/entity-record-ru-aff87f027f11.md)

*Дочерние типы:* [ИмяНабораКонстант.Запись](../../wiki/stdlib/constantssetname-record-ru-0435fbfdf30e.md)

---

## Свойства

### КлючЗаписи

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
КлючЗаписи: НаборКонстант.КлючЗаписи
```

Значения полей из ключа соответствуют значениям (ключевых полей) в самой записи.

#### Примеры

```xbsl
метод ПолучитьКлюч(КурсыВалют: КурсыВалют.Запись): КурсыВалют.КлючЗаписи 
    возврат КурсыВалют.КлючЗаписи 
;
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
