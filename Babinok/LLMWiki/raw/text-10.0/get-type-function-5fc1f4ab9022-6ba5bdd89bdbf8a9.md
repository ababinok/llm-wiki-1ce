# Функция ПолучитьТип

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/get-type-function/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/get-type-function/index.html
> SHA256: 70fcd339af0a081801bd336fb1221372f9a85f130ca21779c9499b7749217973
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Эта функция определяет тип значения. Она имеет следующий синтаксис:

```xbql
выражение.ПолучитьТип(считать-null-типом-null)
```

Выражение может быть любого типа. Значением параметра ***считать-null-типом-null*** определяется поведение для операндов `Null`:

- `Истина`
  
  — для операндов
  
  `Null`
  
  возвращается
  
  `Null`
  
  .
- `Ложь`
  
  — для операндов
  
  `Null`
  
  возвращается
  
  `Тип(Null)`
  
  .

Параметр ***считать-null-типом-null*** не обязательный, значение по умолчанию — `Ложь`.

Пример:

```xbql
Т.Поставщик.ПолучитьТип()
```
