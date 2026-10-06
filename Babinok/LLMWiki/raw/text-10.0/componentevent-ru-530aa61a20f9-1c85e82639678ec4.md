# СобытиеКомпонента

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/ComponentEvent_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/ComponentEvent_ru/index.html
> SHA256: ba3a692789fd4c485774c5d84613f72eea07d73d8115c61e8f6fafb10fbe2f59
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::СобытиеКомпонента` `Доступность: КлиентИСервер`

Является базовым типом для объектов, которые содержат входные и выходные параметры событий компонентов.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ПараметрыЗакрытияФормы](../../wiki/interface/formcloseparams-ru-b4203dc56e56.md), [СобытиеПередИзменением](../../wiki/interface/beforechangeevent-ru-5bdd44f42514.md), [СобытиеПриИзменении](../../wiki/interface/onchangeevent-ru-d20e6d864b48.md), [СобытиеПриИзмененииМасштабаДиаграммыГанта](../../wiki/interface/onganttchartscalechangeevent-ru-3c97308eb74e.md), [СобытиеПриНажатии](../../wiki/interface/onclickevent-ru-15fc28e42f99.md), [СобытиеПриНажатииНаГеографическуюКарту](../../wiki/interface/ongeographicmapclickevent-ru-372d6de91daa.md), [СобытиеПриНажатииНаДиаграммуГанта](../../wiki/interface/onganttchartclickevent-ru-e25e0ffcb4d2.md), [СобытиеПриРедактированииСтроки](../../wiki/interface/onroweditevent-ru-c21cf86ca19c.md), [СобытиеПриСозданииСтроки](../../wiki/interface/onrowcreateevent-ru-b62297d7b8bc.md), [СобытиеСДанными](../../wiki/interface/eventwithdata-ru-99142c162a43.md)

---

## Конструкторы

### СобытиеКомпонента

`Доступность: КлиентИСервер`

```
СобытиеКомпонента()
```

Создает пустой объект

[СобытиеКомпонента](../../wiki/interface/componentevent-ru-530aa61a20f9.md)

.

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

Строковое представление объекта.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/interface/componentevent-ru-530aa61a20f9.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
