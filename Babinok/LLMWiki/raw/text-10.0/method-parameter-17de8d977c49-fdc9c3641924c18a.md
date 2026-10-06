# Параметр метода

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/terms/method-parameter/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/terms/method-parameter/index.html
> SHA256: 59365208195695b991b8a18ceb667b652db43f36aeacd5d943f971f7f321801b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Параметр метода — это именованная переменная, через которую тело метода получает значение при вызове. Параметры объявляются в сигнатуре метода с указанием их типов и действуют как локальные переменные внутри его тела.

```xbsl
// Метод с параметрами Имя и Возраст
метод Приветствовать(Имя: Строка, Возраст: Число): Строка
    возврат "Привет, ${Имя}! Твой возраст: ${Возраст}."
;
```

## См. также

- [Методы](../../wiki/language/methods-in-built-in-script-language-3c568746fa15.md)
