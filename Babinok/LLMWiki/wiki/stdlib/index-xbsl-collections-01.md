# XBSL: Std::Collections

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [mutablecollection-ru-8bf8ed99ab14-cd9504cab2ac530f](../../raw/text_10_0/mutablecollection-ru-8bf8ed99ab14-cd9504cab2ac530f.md); [mutableset-ru-b964190c77e2-6ff45661a30e3df1](../../raw/text_10_0/mutableset-ru-b964190c77e2-6ff45661a30e3df1.md); [mutablemap-ru-b0e92a5fc29d-9ee23e3c7c22ab4e](../../raw/text_10_0/mutablemap-ru-b0e92a5fc29d-9ee23e3c7c22ab4e.md); [mutablearray-ru-37e20d0db52d-5a191ecb2821441f](../../raw/text_10_0/mutablearray-ru-37e20d0db52d-5a191ecb2821441f.md); [collection-ru-3bc2025a9946-fd9b2e4a925100d5](../../raw/text_10_0/collection-ru-3bc2025a9946-fd9b2e4a925100d5.md); [array-ru-f0659b9628e1-f39996d85ccc086c](../../raw/text_10_0/array-ru-f0659b9628e1-f39996d85ccc086c.md); [set-ru-629ffebe489c-ca9c034f43fa0de8](../../raw/text_10_0/set-ru-629ffebe489c-ca9c034f43fa0de8.md); [map-ru-075f0ef55c6b-ede7e9c4b095d47c](../../raw/text_10_0/map-ru-075f0ef55c6b-ede7e9c4b095d47c.md); [readablecollection-ru-7f954f257c24-cbe85ac7c6feab75](../../raw/text_10_0/readablecollection-ru-7f954f257c24-cbe85ac7c6feab75.md); [readableset-ru-6c31217c511a-444e0abc1cb207f5](../../raw/text_10_0/readableset-ru-6c31217c511a-444e0abc1cb207f5.md); [readablemap-ru-8fb134a1c222-a202421b9ccdc03d](../../raw/text_10_0/readablemap-ru-8fb134a1c222-a202421b9ccdc03d.md); [readablearray-ru-6bae9724f632-54c5ec0226e4c0fd](../../raw/text_10_0/readablearray-ru-6bae9724f632-54c5ec0226e4c0fd.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Оглавление раздела](overview.md) · [Общий индекс](../index.md)

| Статья | Краткое описание | Источник |
| --- | --- | --- |
| [ИзменяемаяКоллекция — Программный тип XBSL: Std / Collections](mutablecollection-ru-8bf8ed99ab14.md) | ТипЭлемента: тип элементов коллекции. | [Raw](../../raw/text_10_0/mutablecollection-ru-8bf8ed99ab14-cd9504cab2ac530f.md) |
| [ИзменяемоеМножество — Программный тип XBSL: Std / Collections](mutableset-ru-b964190c77e2.md) | ТипЭлемента: тип элементов множества. | [Raw](../../raw/text_10_0/mutableset-ru-b964190c77e2-6ff45661a30e3df1.md) |
| [ИзменяемоеСоответствие — Программный тип XBSL: Std / Collections](mutablemap-ru-b0e92a5fc29d.md) | ТипКлюча: тип ключей соответствия. | [Raw](../../raw/text_10_0/mutablemap-ru-b0e92a5fc29d-9ee23e3c7c22ab4e.md) |
| [ИзменяемыйМассив — Программный тип XBSL: Std / Collections](mutablearray-ru-37e20d0db52d.md) | ТипЭлемента: тип элементов массива. | [Raw](../../raw/text_10_0/mutablearray-ru-37e20d0db52d-5a191ecb2821441f.md) |
| [Коллекция — Программный тип XBSL: Std / Collections](collection-ru-3bc2025a9946.md) | ТипЭлемента: тип элементов коллекции. | [Raw](../../raw/text_10_0/collection-ru-3bc2025a9946-fd9b2e4a925100d5.md) |
| [Массив — Программный тип XBSL: Std / Collections](array-ru-f0659b9628e1.md) | ТипЭлемента: тип элементов массива. | [Raw](../../raw/text_10_0/array-ru-f0659b9628e1-f39996d85ccc086c.md) |
| [Множество — Программный тип XBSL: Std / Collections](set-ru-629ffebe489c.md) | ТипЭлемента: тип элементов множества. | [Raw](../../raw/text_10_0/set-ru-629ffebe489c-ca9c034f43fa0de8.md) |
| [Соответствие — Программный тип XBSL: Std / Collections](map-ru-075f0ef55c6b.md) | ТипКлюча: тип ключей соответствия. | [Raw](../../raw/text_10_0/map-ru-075f0ef55c6b-ede7e9c4b095d47c.md) |
| [ЧитаемаяКоллекция — Программный тип XBSL: Std / Collections](readablecollection-ru-7f954f257c24.md) | ТипЭлемента: тип элементов коллекции. | [Raw](../../raw/text_10_0/readablecollection-ru-7f954f257c24-cbe85ac7c6feab75.md) |
| [ЧитаемоеМножество — Программный тип XBSL: Std / Collections](readableset-ru-6c31217c511a.md) | ТипЭлемента: тип элементов множества. | [Raw](../../raw/text_10_0/readableset-ru-6c31217c511a-444e0abc1cb207f5.md) |
| [ЧитаемоеСоответствие — Программный тип XBSL: Std / Collections](readablemap-ru-8fb134a1c222.md) | ТипКлюча: тип ключей соответствия. | [Raw](../../raw/text_10_0/readablemap-ru-8fb134a1c222-a202421b9ccdc03d.md) |
| [ЧитаемыйМассив — Программный тип XBSL: Std / Collections](readablearray-ru-6bae9724f632.md) | ТипЭлемента: тип элементов массива. | [Raw](../../raw/text_10_0/readablearray-ru-6bae9724f632-54c5ec0226e4c0fd.md) |
