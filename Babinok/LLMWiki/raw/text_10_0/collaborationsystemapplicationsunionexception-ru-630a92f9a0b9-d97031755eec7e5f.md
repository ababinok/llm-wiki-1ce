# ИсключениеОбъединенияПриложенийСистемыВзаимодействия

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemApplicationsUnionException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemApplicationsUnionException_ru/index.html
> SHA256: 63ffe2bc2b74730ab6768c10a70e61bc9e2d142a6b17023ad571016424cc6747
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::СистемаВзаимодействия::ИсключениеОбъединенияПриложенийСистемыВзаимодействия` `Доступность: Сервер`

Исключение, выбрасываемое при ошибках объединения приложений в системе взаимодействия.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [ИсключениеСистемыВзаимодействия](../../wiki/integration/collaborationsystemexception-ru-f8d82f9023f2.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

Объединение текущего приложения с несуществующим приложениям.

```xbsl
знч ИдТекущегоПриложения = СистемаВзаимодействия.ПолучитьТекущееПриложение().Ид
знч ИдПарногоПриложения = Ууид{a810ec80-2768-44c7-85da-bb56ba8dafa0}

знч ОбъединениеПриложений = новый ОбъединениеПриложенийВзаимодействия(
    ИдТекущегоПриложения,
    ИдПарногоПриложения,
    РежимСопоставленияПользователейВзаимодействия.ПоИмени,
    Ложь
)

попытка
    СистемаВзаимодействия.ОбъединитьПриложения(ОбъединениеПриложений)
поймать Исключение: ИсключениеОбъединенияПриложенийСистемыВзаимодействия
    // Одно из приложений взаимодействия не существует. Объединение приложений не возможно.
    // ...
;    
```

---

## Список унаследованных методов

### Исключение

[ВСтроку](../../wiki/stdlib/exception-ru-ed2632721976.md)

[Информация](../../wiki/stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../../wiki/stdlib/exception-ru-ed2632721976.md), [Описание](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../../wiki/stdlib/exception-ru-ed2632721976.md), [Причина](../../wiki/stdlib/exception-ru-ed2632721976.md)

## Список унаследованных событий

### Исключение

[Ид](../../wiki/stdlib/exception-ru-ed2632721976.md), [Описание](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../../wiki/stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../../wiki/stdlib/exception-ru-ed2632721976.md), [Причина](../../wiki/stdlib/exception-ru-ed2632721976.md)
