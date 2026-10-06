# Именованный аргумент

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/terms/named-argument/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/terms/named-argument/index.html
> SHA256: 34cedf2fa3269aba2412a94af8bacf8744670a50c62c5b3c2db61eb33dd2ffeb
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Именованный аргумент — это аргумент, для которого указано имя параметра, в который его нужно передать.

В примере ниже описан метод `ОбъемФигуры()` с параметрами `Длина`, `Ширина` и `Высота`. При вызове метода аргумент `120` передается в третий параметр `Высота`, а аргумент `80` — во второй параметр `Ширина`.

```xbsl
метод ОбъемФигуры(Длина: Число, Ширина: Число, Высота: Число): Строка
    возврат "Объем равен ${Длина*Ширина*Высота}"
;

метод Скрипт()
    Объем(100, Высота = 120, Ширина = 80)
;
```

## См. также

- [Методы](../../wiki/language/methods-in-built-in-script-language-3c568746fa15.md)
