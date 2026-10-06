# XBSL: Std::InputOutput

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [temporarywritablestream-ru-402408acf5bc-050dbf05b9618891](../../raw/text_10_0/temporarywritablestream-ru-402408acf5bc-050dbf05b9618891.md); [datawriter-ru-dad488a6c9ae-8ef24a73a81bc26e](../../raw/text_10_0/datawriter-ru-dad488a6c9ae-8ef24a73a81bc26e.md); [inputoutputexception-ru-ceba5f672999-6a72484af5b2a55e](../../raw/text_10_0/inputoutputexception-ru-ceba5f672999-6a72484af5b2a55e.md); [bytesordermark-ru-b01380f240b7-58beb8cb2fc06fbe](../../raw/text_10_0/bytesordermark-ru-b01380f240b7-58beb8cb2fc06fbe.md); [datawriteroptions-ru-75f548a28e4b-6a627b22f6a0a1b5](../../raw/text_10_0/datawriteroptions-ru-75f548a28e4b-6a627b22f6a0a1b5.md); [datareaderoptions-ru-81757cccef44-851c2c3507c3ecbd](../../raw/text_10_0/datareaderoptions-ru-81757cccef44-851c2c3507c3ecbd.md); [bytesorder-ru-17583f581f23-4ddffde28f552c3b](../../raw/text_10_0/bytesorder-ru-17583f581f23-4ddffde28f552c3b.md); [writablestream-ru-db9a09ef1933-debde3a521b3f95b](../../raw/text_10_0/writablestream-ru-db9a09ef1933-debde3a521b3f95b.md); [readablestream-ru-c306ee00c3af-02835c1028f80a8a](../../raw/text_10_0/readablestream-ru-c306ee00c3af-02835c1028f80a8a.md); [readdataresult-ru-cb902b234ec0-05a2bc2137a9f6c8](../../raw/text_10_0/readdataresult-ru-cb902b234ec0-05a2bc2137a9f6c8.md); [stringwritablestream-ru-60a519728c66-f9ee8ebe97b714a8](../../raw/text_10_0/stringwritablestream-ru-60a519728c66-f9ee8ebe97b714a8.md); [datareader-ru-d6f053534f19-ed4df1cad3e974ef](../../raw/text_10_0/datareader-ru-d6f053534f19-ed4df1cad3e974ef.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Оглавление раздела](overview.md) · [Общий индекс](../index.md)

| Статья | Краткое описание | Источник |
| --- | --- | --- |
| [ВременныйПотокЗаписи — Программный тип XBSL: Std / InputOutput](temporarywritablestream-ru-402408acf5bc.md) | Поток для записи данных, хранящий их в памяти, пока размер не превышает указанное при создании ограничение. | [Raw](../../raw/text_10_0/temporarywritablestream-ru-402408acf5bc-050dbf05b9618891.md) |
| [ЗаписьДанных — Программный тип XBSL: Std / InputOutput](datawriter-ru-dad488a6c9ae.md) | *Базовые типы:* Объект | [Raw](../../raw/text_10_0/datawriter-ru-dad488a6c9ae-8ef24a73a81bc26e.md) |
| [ИсключениеВводаВывода — Программный тип XBSL: Std / InputOutput](inputoutputexception-ru-ceba5f672999.md) | Исключение, выбрасываемое при ошибках ввода-вывода. | [Raw](../../raw/text_10_0/inputoutputexception-ru-ceba5f672999-6a72484af5b2a55e.md) |
| [МеткаПорядкаБайтов — Программный тип XBSL: Std / InputOutput](bytesordermark-ru-b01380f240b7.md) | Стратегия добавления метки порядка байтов (BOM) при записи в поток. | [Raw](../../raw/text_10_0/bytesordermark-ru-b01380f240b7-58beb8cb2fc06fbe.md) |
| [НастройкиЗаписиДанных — Программный тип XBSL: Std / InputOutput](datawriteroptions-ru-75f548a28e4b.md) | Настройки для ЗаписьДанных. | [Raw](../../raw/text_10_0/datawriteroptions-ru-75f548a28e4b-6a627b22f6a0a1b5.md) |
| [НастройкиЧтенияДанных — Программный тип XBSL: Std / InputOutput](datareaderoptions-ru-81757cccef44.md) | Настройки для объекта ЧтениеДанных | [Raw](../../raw/text_10_0/datareaderoptions-ru-81757cccef44-851c2c3507c3ecbd.md) |
| [ПорядокБайтов — Программный тип XBSL: Std / InputOutput](bytesorder-ru-17583f581f23.md) | Порядок байтов при хранении информации в памяти. | [Raw](../../raw/text_10_0/bytesorder-ru-17583f581f23-4ddffde28f552c3b.md) |
| [ПотокЗаписи — Программный тип XBSL: Std / InputOutput](writablestream-ru-db9a09ef1933.md) | Однонаправленный поток записи двоичных данных. | [Raw](../../raw/text_10_0/writablestream-ru-db9a09ef1933-debde3a521b3f95b.md) |
| [ПотокЧтения — Программный тип XBSL: Std / InputOutput](readablestream-ru-c306ee00c3af.md) | Однонаправленный поток чтения данных. | [Raw](../../raw/text_10_0/readablestream-ru-c306ee00c3af-02835c1028f80a8a.md) |
| [РезультатЧтенияДанных — Программный тип XBSL: Std / InputOutput](readdataresult-ru-cb902b234ec0.md) | Используется для сохранения прочитанных данных и дальнейших операций с ними. | [Raw](../../raw/text_10_0/readdataresult-ru-cb902b234ec0-05a2bc2137a9f6c8.md) |
| [СтроковыйПотокЗаписи — Программный тип XBSL: Std / InputOutput](stringwritablestream-ru-60a519728c66.md) | Поток записи данных в строку. | [Raw](../../raw/text_10_0/stringwritablestream-ru-60a519728c66-f9ee8ebe97b714a8.md) |
| [ЧтениеДанных — Программный тип XBSL: Std / InputOutput](datareader-ru-d6f053534f19.md) | Предназначен для чтения данных из потока. | [Raw](../../raw/text_10_0/datareader-ru-d6f053534f19-ed4df1cad3e974ef.md) |
