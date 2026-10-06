# РежимЭкранированияHtml

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [htmlescapemode-ru-1fef8d43d399-f191ddd68fa9d4f1](../../raw/text-10.0/htmlescapemode-ru-1fef8d43d399-f191ddd68fa9d4f1.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / HtmlDocument.

Имена для поиска: `РежимЭкранированияHtml`, `HtmlEscapeMode`, `Стд::ДокументHtml::РежимЭкранированияHtml`, `Std::HtmlDocument::HtmlEscapeMode`.

## Обзор

Перечисление для режима экранирования текста в html.

## Документированный контракт и примеры

`Стд::ДокументHtml::РежимЭкранированияHtml` `Доступность: КлиентИСервер`

Перечисление для режима экранирования текста в html.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Перечисление](../stdlib/enum-ru-a7a357b96b4c.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md)

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

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

### Перечисление

[ВСтроку](../stdlib/enum-ru-a7a357b96b4c.md)

[Представление](../stdlib/enum-ru-a7a357b96b4c.md)

### Представляемое

## Список унаследованных свойств

### Перечисление

[Индекс](../stdlib/enum-ru-a7a357b96b4c.md)

## See Also

- [Навигатор раздела](../stdlib/overview.md)
- [Стд::ДокументHtml — Пространство имён XBSL: Std](htmldocument-3aa09cdfb98c.md)
- [Коллекции и точные контракты стандартной библиотеки](../stdlib/collections-and-contracts.md)

Оригинал: [РежимЭкранированияHtml](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/HtmlDocument/HtmlEscapeMode_ru/).
