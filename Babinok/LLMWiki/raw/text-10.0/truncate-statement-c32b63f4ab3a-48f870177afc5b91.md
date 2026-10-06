# Оператор ОБРЕЗАТЬ

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/truncate-statement/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/truncate-statement/index.html
> SHA256: f8f98d2339709012e4be9a42268884121ae7b1903a1ee2a620bc17e7b1d8e7a3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Удаляет все строки во временной таблице. Оператор `ОБРЕЗАТЬ` похож на оператор [УДАЛИТЬ](../../wiki/project/delete-statement-e6de4fd70bea.md) без предложения `ГДЕ`, но `ОБРЕЗАТЬ` выполняется быстрее и требует меньших ресурсов системы. Оператор имеет следующий синтаксис:

```xbql
ОБРЕЗАТЬ
    имя-временной-таблицы
```

В качестве результата запроса возвращается пустой результат (без строк и полей).
