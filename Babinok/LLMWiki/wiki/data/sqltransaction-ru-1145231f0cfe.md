# ТранзакцияSql

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [sqltransaction-ru-1145231f0cfe-7f7990a0dc35988b](../../raw/text-10.0/sqltransaction-ru-1145231f0cfe-7f7990a0dc35988b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Database / Sql.

Имена для поиска: `ТранзакцияSql`, `SqlTransaction`, `Стд::БазаДанных::Sql::ТранзакцияSql`, `Std::Database::Sql::SqlTransaction`.

## Обзор

*Базовые типы:* [Закрываемое](../stdlib/closeable-ru-67cd73fca69d.md), [Контекст](../stdlib/context-ru-aa03c6bdd5aa.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::БазаДанных::Sql::ТранзакцияSql` `Доступность: Сервер`

Транзакция при вызове базы.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Закрываемое](../stdlib/closeable-ru-67cd73fca69d.md), [Контекст](../stdlib/context-ru-aa03c6bdd5aa.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Методы

### Закрыть

`Доступность: Сервер`

```
Закрыть()
```

Закрывает текущую транзакцию. Если транзакция не зафиксирована, то она откатывается.

**Переопределение** [Закрываемое::Закрыть](../stdlib/closeable-ru-67cd73fca69d.md)

---

### Откатить

`Доступность: Сервер`

```
Откатить()
```

Закрывает транзакцию и откатывает ее.

---

### Фиксировать

`Доступность: Сервер`

```
Фиксировать()
```

Закрывает транзакцию и фиксирует ее.

---

## Список унаследованных методов

### Закрываемое

[Закрыть](../stdlib/closeable-ru-67cd73fca69d.md) [(Переопределение)](sqltransaction-ru-1145231f0cfe.md)

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::БазаДанных::Sql — Пространство имён XBSL: Std / Database](sql-35c66dd0c5b4.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [ТранзакцияSql](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Database/Sql/SqlTransaction_ru/).
