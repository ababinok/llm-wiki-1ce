# Объявления методов

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/method-declarations/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/method-declarations/index.html
> SHA256: 7ba165c901d21a864212f37ee76d542fedb66dd94b43fb19a743e641bd692c5f
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Необязательные параметры (со значениями по умолчанию) должны располагаться после обязательных параметров (без значений по умолчанию).

Правильно. [Описание иллюстрации](../figures/e84cee6e0d7036af176153092a96bb7ffe5f858bf23d616f7cfc983a97a2de5f-ba77891b83aec8c5.md)

```xbsl
метод НовоеСообщение(
    Вид: Строка,
    Дата = ""
): Соответствие<Строка,Строка>

    возврат {"тип": Вид, "дата": Дата}
;
```

Неправильно. [Описание иллюстрации](../figures/603d54fd2915a5d2131847b25291afd1287a94423523671c5d183e102fd7c34e-e876f584ea679688.md)

```xbsl
метод НовоеСообщение(
    Дата = "",
    Вид: Строка
): Соответствие<Строка,Строка>

    возврат {"тип": Вид, "дата": Дата}
;
```

## См. также

- [Методы](../../wiki/language/methods-in-built-in-script-language-3c568746fa15.md)
