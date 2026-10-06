# ТранзакцияSql

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Database/Sql/SqlTransaction_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Database/Sql/SqlTransaction_ru/index.html
> SHA256: 9d179765857940af20daead6c5094baf23bebff35164b71608af64613e7f1b42
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::БазаДанных::Sql::ТранзакцияSql` `Доступность: Сервер`

Транзакция при вызове базы.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Закрываемое](../../wiki/stdlib/closeable-ru-67cd73fca69d.md), [Контекст](../../wiki/stdlib/context-ru-aa03c6bdd5aa.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Методы

### Закрыть

`Доступность: Сервер`

```
Закрыть()
```

Закрывает текущую транзакцию. Если транзакция не зафиксирована, то она откатывается.

**Переопределение** [Закрываемое::Закрыть](../../wiki/stdlib/closeable-ru-67cd73fca69d.md)

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

[Закрыть](../../wiki/stdlib/closeable-ru-67cd73fca69d.md) [(Переопределение)](../../wiki/data/sqltransaction-ru-1145231f0cfe.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
