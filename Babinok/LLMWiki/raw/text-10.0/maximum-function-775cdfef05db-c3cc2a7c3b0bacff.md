# Функция МАКСИМУМ

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/maximum-function/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/maximum-function/index.html
> SHA256: 32921d6bf5e1ba2e15cee5c5947ba419cd0b05787caaf797b203a7639bfffdcf
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Функция вычисляет максимальное значение из всех попавших в выборку значений поля. Она имеет следующий синтаксис:

```xbql
МАКСИМУМ(операнд)
```

Если выборка, по которой рассчитывается ***операнд***, пустая, то результатом функции будет `Null`.

Пример:

```xbql
ВЫБРАТЬ
    МАКСИМУМ(Сотрудники.Возраст) КАК МаксимальныйВозраст
ИЗ
    Сотрудники КАК Сотрудники
```
