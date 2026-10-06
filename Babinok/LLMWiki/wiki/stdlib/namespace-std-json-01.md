# Стд::Json

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [jsonignoreproperty-ru-2025b10a49b4-42d7d949c609e8fe](../../raw/text-10.0/jsonignoreproperty-ru-2025b10a49b4-42d7d949c609e8fe.md); [jsonobject-ru-1556e7381e55-d7be8c363092d456](../../raw/text-10.0/jsonobject-ru-1556e7381e55-d7be8c363092d456.md); [jsonproperty-ru-6c3444d3e337-6d135fb7cf61aa27](../../raw/text-10.0/jsonproperty-ru-6c3444d3e337-6d135fb7cf61aa27.md); [jsonenumitem-ru-4547bcf79195-d3255907ec55fdd8](../../raw/text-10.0/jsonenumitem-ru-4547bcf79195-d3255907ec55fdd8.md); [jsonnodekind-ru-e0ea36aba727-b40287a7c42e060a](../../raw/text-10.0/jsonnodekind-ru-e0ea36aba727-b40287a7c42e060a.md); [jsonwriter-ru-9ec154ed880b-41ab3e3bfa574b84](../../raw/text-10.0/jsonwriter-ru-9ec154ed880b-41ab3e3bfa574b84.md); [jsonwriterexception-ru-9073a0c1344f-fbaf750734773a80](../../raw/text-10.0/jsonwriterexception-ru-9073a0c1344f-fbaf750734773a80.md); [jsonreaderexception-ru-62be4dbb30ff-c3f2e17aba420a91](../../raw/text-10.0/jsonreaderexception-ru-62be4dbb30ff-c3f2e17aba420a91.md); [jsonwriteroptions-ru-1ea966b35ac8-51dab6dfa2590d07](../../raw/text-10.0/jsonwriteroptions-ru-1ea966b35ac8-51dab6dfa2590d07.md); [jsonobjectswriteoptions-ru-0d7adda78618-f8e9899b47c419b1](../../raw/text-10.0/jsonobjectswriteoptions-ru-0d7adda78618-f8e9899b47c419b1.md); [jsonobjectsreadoptions-ru-4d9dc4d34433-5041b67fb003fe92](../../raw/text-10.0/jsonobjectsreadoptions-ru-4d9dc4d34433-5041b67fb003fe92.md); [jsonlinebreak-ru-ea09a263d9f1-f109653357e88e97](../../raw/text-10.0/jsonlinebreak-ru-ea09a263d9f1-f109653357e88e97.md); [jsontypewritemode-ru-ece10c6fb9a3-af685caf93b40812](../../raw/text-10.0/jsontypewritemode-ru-ece10c6fb9a3-af685caf93b40812.md); [jsonserialization-ru-d810a802893e-5fb1a04de4a1758e](../../raw/text-10.0/jsonserialization-ru-d810a802893e-5fb1a04de4a1758e.md); [json-c14cfb07c84b-940006ab0675f2dd](../../raw/text-10.0/json-c14cfb07c84b-940006ab0675f2dd.md); [jsoninstantformat-ru-d2ded8fa0056-7aa29d8540c298be](../../raw/text-10.0/jsoninstantformat-ru-d2ded8fa0056-7aa29d8540c298be.md); [jsonreader-ru-ff27f8463f3e-86d5566c3325a094](../../raw/text-10.0/jsonreader-ru-ff27f8463f3e-86d5566c3325a094.md); [jsoncharactersescapemode-ru-17e3f26f2b0b-95db55d6c077bf9f](../../raw/text-10.0/jsoncharactersescapemode-ru-17e3f26f2b0b-95db55d6c077bf9f.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Пространства имён](namespaces.md)

- [JsonИгнорироватьСвойство — Программный тип XBSL: Std / Json](../integration/jsonignoreproperty-ru-2025b10a49b4.md)
- [JsonОбъект — Программный тип XBSL: Std / Json](../integration/jsonobject-ru-1556e7381e55.md)
- [JsonСвойство — Программный тип XBSL: Std / Json](../integration/jsonproperty-ru-6c3444d3e337.md)
- [JsonЭлементПеречисления — Программный тип XBSL: Std / Json](../integration/jsonenumitem-ru-4547bcf79195.md)
- [ВидУзлаJson — Программный тип XBSL: Std / Json](../integration/jsonnodekind-ru-e0ea36aba727.md)
- [ЗаписьJson — Программный тип XBSL: Std / Json](../integration/jsonwriter-ru-9ec154ed880b.md)
- [ИсключениеЗаписиJson — Программный тип XBSL: Std / Json](../integration/jsonwriterexception-ru-9073a0c1344f.md)
- [ИсключениеЧтенияJson — Программный тип XBSL: Std / Json](../integration/jsonreaderexception-ru-62be4dbb30ff.md)
- [НастройкиЗаписиJson — Программный тип XBSL: Std / Json](../integration/jsonwriteroptions-ru-1ea966b35ac8.md)
- [НастройкиЗаписиОбъектовJson — Программный тип XBSL: Std / Json](../integration/jsonobjectswriteoptions-ru-0d7adda78618.md)
- [НастройкиЧтенияОбъектовJson — Программный тип XBSL: Std / Json](../integration/jsonobjectsreadoptions-ru-4d9dc4d34433.md)
- [ПереносСтрокJson — Программный тип XBSL: Std / Json](../integration/jsonlinebreak-ru-ea09a263d9f1.md)
- [РежимЗаписиТипаJson — Программный тип XBSL: Std / Json](../integration/jsontypewritemode-ru-ece10c6fb9a3.md)
- [СериализацияJson — Программный тип XBSL: Std / Json](../integration/jsonserialization-ru-d810a802893e.md)
- [Стд::Json — Пространство имён XBSL: Std](../integration/json-c14cfb07c84b.md)
- [ФорматМоментаJson — Программный тип XBSL: Std / Json](../integration/jsoninstantformat-ru-d2ded8fa0056.md)
- [ЧтениеJson — Программный тип XBSL: Std / Json](../integration/jsonreader-ru-ff27f8463f3e.md)
- [ЭкранированиеСимволовJson — Программный тип XBSL: Std / Json](../integration/jsoncharactersescapemode-ru-17e3f26f2b0b.md)
