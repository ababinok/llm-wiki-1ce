# ИсключениеЗапретаДоступаСистемыВзаимодействия

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemAccessDeniedException_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/CollaborationSystem/CollaborationSystemAccessDeniedException_ru/index.html
> SHA256: 1eabd1e9306f14f9cd6a2a4252451672c700db0b7ccb10aa8007779c7f619e45
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::СистемаВзаимодействия::ИсключениеЗапретаДоступаСистемыВзаимодействия` `Доступность: Сервер`

Исключение, выбрасываемое если нет доступа к запрашиваемому объекту.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../../wiki/stdlib/exception-ru-ed2632721976.md), [ИсключениеСистемыВзаимодействия](../../wiki/integration/collaborationsystemexception-ru-f8d82f9023f2.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Примеры

**Общие примеры**

```xbsl
// вымышленный собеседник
знч ИдСобеседника = Ууид{1da570ae-4481-11ed-b878-0242ac120002}
знч Участники = [ИдСобеседника]

пер ИдНовогоОбсуждения: Ууид?
попытка
    ИдНовогоОбсуждения = СистемаВзаимодействия.СоздатьОбсуждение(Участники, "Новое обсуждение")
поймать Исключение: ИсключениеЗапретаДоступаСистемыВзаимодействия
    // Нельзя создавать обсуждения, если ты не являешься их участником, т.к. не будет доступа к этому объекту
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
