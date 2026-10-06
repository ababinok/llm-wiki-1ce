# Функция МИНИМУМ

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/minimum-function/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/minimum-function/index.html
> SHA256: 25be63732ab0a4d0bea846ee4f9e434091d63b53abe2adabeb3c26d0f24ebead
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Функция вычисляет минимальное значение из всех попавших в выборку значений поля. Она имеет следующий синтаксис:

```xbql
МИНИМУМ(операнд)
```

Если выборка, по которой рассчитывается ***операнд***, пустая, то результатом функции будет `Null`.

Пример:

```xbql
ВЫБРАТЬ
    МИНИМУМ(Сотрудники.Возраст) КАК МинимальныйВозраст
ИЗ
    Сотрудники КАК Сотрудники
```
