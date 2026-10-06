# УзелТипДокументаHtml

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HtmlDocument/HtmlDocumentTypeNode_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/HtmlDocument/HtmlDocumentTypeNode_ru/index.html
> SHA256: 0daf1eed6cd9cd492e48c056db198c94a736abbbbf2b456a5c04f02c48561bbf
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ДокументHtml::УзелТипДокументаHtml` `Доступность: Сервер`

Терминальный узел соответствующий конструкции `<!DOCTYPE>` в html.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [УзелHtml](../../wiki/data/htmlnode-ru-31832172d5d4.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ТерминальныйУзелСоответствующийКонструкции(Документ: ДокументHtml)
    Документ.УстановитьТипДокумента(новый УзелТипДокументаHtml("html", "-//W3C//DTD HTML 4.01 Transitional//EN",
        "http://www.w3.org/TR/html4/loose.dtd"))
    /* Получим:
    <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
    <html>
     <head>
    ...
    */
;
```

---

## Конструкторы

### УзелТипДокументаHtml

`Доступность: Сервер`

```
УзелТипДокументаHtml(
  Имя: Строка,
  ОткрытыйИд: Строка,
  СистемныйИд: Строка)
```

Создает узел типа документа.

---

## Свойства

### Имя

`Доступность: Сервер` `ТолькоЧтение`

```
Имя: Строка
```

Имя документа или пустая строка, если не задано, обычно равен строке "html".

---

### ОткрытыйИд

`Доступность: Сервер` `ТолькоЧтение`

```
ОткрытыйИд: Строка
```

Публичный ид из атрибута "publicId" или пустая строка, если не задано. Для HTML 5 пустая строка.

---

### СистемныйИд

`Доступность: Сервер` `ТолькоЧтение`

```
СистемныйИд: Строка
```

Системный ид документа из атрибута "systemId" или пустая строка, если не задано. Для HTML 5 пустая строка.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает cтроку с объявлением типа документа.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/data/htmldocumenttypenode-ru-caa3f2ed10e8.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### УзелHtml

[ВнешнийКод](../../wiki/data/htmlnode-ru-31832172d5d4.md)

[ВставитьКопииУзловДоТекущего](../../wiki/data/htmlnode-ru-31832172d5d4.md)

[ВставитьКопииУзловПослеТекущего](../../wiki/data/htmlnode-ru-31832172d5d4.md)

[ОбойтиВГлубину](../../wiki/data/htmlnode-ru-31832172d5d4.md)

[Удалить](../../wiki/data/htmlnode-ru-31832172d5d4.md)

## Список унаследованных свойств

### УзелHtml

[ДиапазонВКоде](../../wiki/data/htmlnode-ru-31832172d5d4.md), [ДокументВладелец](../../wiki/data/htmlnode-ru-31832172d5d4.md), [ДочерниеУзлы](../../wiki/data/htmlnode-ru-31832172d5d4.md), [ПредыдущийСосед](../../wiki/data/htmlnode-ru-31832172d5d4.md), [Родитель](../../wiki/data/htmlnode-ru-31832172d5d4.md), [СледующийСосед](../../wiki/data/htmlnode-ru-31832172d5d4.md)
