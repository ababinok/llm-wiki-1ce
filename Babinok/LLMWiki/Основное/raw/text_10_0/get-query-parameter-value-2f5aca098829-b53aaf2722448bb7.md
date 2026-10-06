# Выражение получения значения параметра запроса

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/get-query-parameter-value/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/get-query-parameter-value/index.html
> SHA256: c19261e4505e5cdf962697c8d03806dc2f8375b2b0bb762abdbd7e1885bc993b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Выражение получения значения параметра запроса имеет следующий синтаксис:

```xbql
&имя-параметра
```

Например:

```xbql
ВЫБРАТЬ
    Сотрудники.Ссылка КАК Ссылка,
    Сотрудники.ФИО КАК ФИО,
    Сотрудники.Возраст КАК Возраст
ИЗ
    Сотрудники КАК Сотрудники
ГДЕ
    Сотрудники.Возраст < &Возраст
УПОРЯДОЧИТЬ ПО
    Сотрудники.ФИО
```
