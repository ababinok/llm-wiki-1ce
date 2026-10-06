# Позиционный аргумент

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/terms/positional-argument/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/terms/positional-argument/index.html
> SHA256: e3e0e0969e320e9734bce36a368328dae596e147b6b7ae8d56972c3b44f0dad3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Позиционный аргумент — это аргумент, который передается в параметр, находящийся в той же позиции.

В примере ниже описан метод `Площадь()` с параметрами `Длина` и `Ширина`. При вызове метода аргумент `105`, находящийся в первой позиции, передается в параметр `Длина`, который тоже находится в первой позиции:

```xbsl
метод Площадь(Длина: Число, Ширина: Число): Строка
    возврат "Площадь равна ${Длина*Ширина}"    
;

метод ВычислитьПлощадь()
    пер Результат = Площадь(105, 71)
;
```

## См. также

- [Методы](../../wiki/language/methods-in-built-in-script-language-3c568746fa15.md)
