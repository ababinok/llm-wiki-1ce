# ПроизвольныеДанныеСтрокиДинамическогоСписка

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/DataSources/DynamicList/CustomDynamicListRowData_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/DataSources/DynamicList/CustomDynamicListRowData_ru/index.html
> SHA256: e8527b3cb7bca0f08d30117604395669ea39009aa93bd55cdfe4b8c4a306a6ac
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ИсточникиДанных::ДинамическийСписок::ПроизвольныеДанныеСтрокиДинамическогоСписка` `Доступность: КлиентИСервер`

Реализация [ДанныеСтрокиДинамическогоСписка](../../wiki/interface/dynamiclistrowdata-ru-944b789a8d8c.md) по умолчаню, содержит значения полей одной записи динамического списка в виде [ЧитаемоеСоответствие](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)<Строка, Объект?>

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [ДанныеСтрокиДинамическогоСписка<Объект>](../../wiki/interface/dynamiclistrowdata-ru-944b789a8d8c.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Операция []

`Только чтение`

```
[Ключ: Строка]: Объект?
```

Возвращает значение поля динамического списка по его имени.

---

## Методы

### КакСоответствие

`Доступность: КлиентИСервер`

```
КакСоответствие(): ЧитаемоеСоответствие<Строка, Объект?>
```

Возвращает значения записи полей динамического списка в виде

[ЧитаемоеСоответствие](../../wiki/stdlib/readablemap-ru-8fb134a1c222.md)

<Строка, Объект?>

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
