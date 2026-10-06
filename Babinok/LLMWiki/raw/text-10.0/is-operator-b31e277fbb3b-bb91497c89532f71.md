# Операция «это»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/is-operator/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/is-operator/index.html
> SHA256: c5b894e78ba52f9247041c4ed30ee8a4bb3c86d19410cd4e963123615e563936
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Вместо отрицания результата проверки следует использовать операцию проверки с отрицанием:

Правильно. [Описание иллюстрации](../figures/e84cee6e0d7036af176153092a96bb7ffe5f858bf23d616f7cfc983a97a2de5f-ba77891b83aec8c5.md)

```xbsl
пер Значение: Строка?
// ...
если Значение это не Строка
    пер Результат = "Это не строка"
;
```

Неправильно. [Описание иллюстрации](../figures/603d54fd2915a5d2131847b25291afd1287a94423523671c5d183e102fd7c34e-e876f584ea679688.md)

```xbsl
пер Значение: Строка?
// ...
если не (Значение это Строка)
    пер Результат = "Это не строка"
;
```

## См. также

- [Операция «это»](../../wiki/language/is-e12cbcb44c3d.md)
