# РежимЭкранированияHtml

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HtmlDocument/HtmlEscapeMode_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/HtmlDocument/HtmlEscapeMode_ru/index.html
> SHA256: 4f507de580497e6c839f9bd51b8425f59a21252954d25a02551e08e5b9260b11
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ДокументHtml::РежимЭкранированияHtml` `Доступность: КлиентИСервер`

Перечисление для режима экранирования текста в html.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Перечисление](../../wiki/stdlib/enum-ru-a7a357b96b4c.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)

---

## Примеры

**Общие примеры**

Ввод: "Hello &<> Å å π 新 there ¾ ©»"

| Кодировка | Режим | Вывод |
| --- | --- | --- |
| Ascii | Базовый | Hello &<> Å å π 新 there ¾ ©» |
| Ascii | Расширенный | Hello &<> Å å π 新 there ¾ ©» |
| Ascii | XHtml | Hello &<> Å å π 新 there ¾ ©» |
| Utf8 | Расширенный | Hello &<> Å å π 新 there ¾ ©» |
| Utf8 | XHtml | Hello &<> Å å π 新 there ¾ ©» |

---

## Элементы

## Свойства

### Xhtml

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Xhtml
```

Для экранирования сущностей для xhtml, только: lt, gt, amp, и quot.

---

### Базовый

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Базовый
```

Для экранирования по умолчанию текста под html - экранирует 106 популярных символов (из списка [https://www.w3.org/TR/2011/WD-html5-20110525/named-character-references.html](https://www.w3.org/TR/2011/WD-html5-20110525/named-character-references.html)).

---

### Расширенный

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Расширенный
```

Для расширенного экранирования текста под html - экранирует 2125 символов (список [https://www.w3.org/TR/2011/WD-html5-20110525/named-character-references.html](https://www.w3.org/TR/2011/WD-html5-20110525/named-character-references.html)).

---

## Список унаследованных методов

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Перечисление

[ВСтроку](../../wiki/stdlib/enum-ru-a7a357b96b4c.md)

[Представление](../../wiki/stdlib/enum-ru-a7a357b96b4c.md)

### Представляемое

## Список унаследованных свойств

### Перечисление

[Индекс](../../wiki/stdlib/enum-ru-a7a357b96b4c.md)
