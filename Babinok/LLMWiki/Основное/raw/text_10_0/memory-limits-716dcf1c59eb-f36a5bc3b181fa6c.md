# Ограничения на выделяемую память

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/memory-limits/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/memory-limits/index.html
> SHA256: ad25a80adaf32478d56a1afced2691a4829b6df8ab511cefdba84f53f1fd8039
> SnapshotCreated: 2026-10-05
> Rendition: verified text

В облаке для объектов некоторых типов установлено ограничение по памяти — 10 Мбайт. При превышении этого ограничения генерируются исключения.

Ниже приведены примеры типов и методов, для которых действует ограничение:

- [`ПотокЧтения`](../../wiki/stdlib/readablestream-ru-c306ee00c3af.md)
  
  :
  
  - [`ПотокЧтения.ПрочитатьКакСтроку()`](../../wiki/stdlib/readablestream-ru-c306ee00c3af.md)
    
    ,
  - [`ПотокЧтения.ПрочитатьКакБайты()`](../../wiki/stdlib/readablestream-ru-c306ee00c3af.md)
    
    ,
- [`СтроковыйПотокЗаписи.СтроковыйПотокЗаписи()`](../../wiki/stdlib/stringwritablestream-ru-60a519728c66.md)
  
  ,
- [`ВременныйПотокЗаписи.ВременныйПотокЗаписи(РазмерБуфера: РазмерБайтов = 100 КБайт)`](../../wiki/stdlib/temporarywritablestream-ru-402408acf5bc.md)
  
  — размер буфера не может превышать установленное ограничение,
- [`ДвоичныйОбъект.ПолучитьБайты()`](../../wiki/data/binaryobject-ru-a65f10db6bb3.md)
  
  ,
- [`СериализацияJson`](../../wiki/integration/jsonserialization-ru-d810a802893e.md)
  
  :
  
  - [`СериализацияJson.ЗаписатьОбъект()`](../../wiki/integration/jsonserialization-ru-d810a802893e.md)
    
    ,
  - [`СериализацияJson.ПрочитатьМассив()`](../../wiki/integration/jsonserialization-ru-d810a802893e.md)
    
    ,
  - [`СериализацияJson.ПрочитатьОбъект()`](../../wiki/integration/jsonserialization-ru-d810a802893e.md)
    
    ,
  - [`СериализацияJson.ПрочитатьСоответствие()`](../../wiki/integration/jsonserialization-ru-d810a802893e.md)
    
    ,
- конкатенация
  
  [`Строк`](../../wiki/stdlib/string-ru-1bac645acacf.md)
  
  — проверяется размер результирующей строки.
