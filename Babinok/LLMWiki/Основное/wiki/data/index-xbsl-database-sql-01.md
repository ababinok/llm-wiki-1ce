# XBSL: Std::Database::Sql

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [sqlquery-ru-81232e8a7d08-9b91c371269db6d5](../../raw/text-10.0/sqlquery-ru-81232e8a7d08-9b91c371269db6d5.md); [sqlquerywithoutselect-ru-7c15635cb95f-5b612563c6a32602](../../raw/text-10.0/sqlquerywithoutselect-ru-7c15635cb95f-5b612563c6a32602.md); [sqlqueryprocedurecall-ru-f81cef4a20b9-b25ba2e81b77a180](../../raw/text-10.0/sqlqueryprocedurecall-ru-f81cef4a20b9-b25ba2e81b77a180.md); [sqlquerywithselect-ru-1d2ee8fe3d18-4e0b0e326589e41a](../../raw/text-10.0/sqlquerywithselect-ru-1d2ee8fe3d18-4e0b0e326589e41a.md); [sqlexception-ru-c108d8de1746-3eb33aeef9ea603a](../../raw/text-10.0/sqlexception-ru-c108d8de1746-3eb33aeef9ea603a.md); [sqlselectresult-ru-b351439e205b-81f0253522588e8c](../../raw/text-10.0/sqlselectresult-ru-b351439e205b-81f0253522588e8c.md); [sqlprocedurecallresult-ru-32a7cafaceba-d91a0ce3ddbe3e85](../../raw/text-10.0/sqlprocedurecallresult-ru-32a7cafaceba-d91a0ce3ddbe3e85.md); [sqlconnection-ru-c5e86d40a6b0-60b5606e186cdd32](../../raw/text-10.0/sqlconnection-ru-c5e86d40a6b0-60b5606e186cdd32.md); [sqldatatype-ru-c79a407c2f77-cf1e2ea1b42522b8](../../raw/text-10.0/sqldatatype-ru-c79a407c2f77-cf1e2ea1b42522b8.md); [sqltransaction-ru-1145231f0cfe-7f7990a0dc35988b](../../raw/text-10.0/sqltransaction-ru-1145231f0cfe-7f7990a0dc35988b.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Оглавление раздела](overview.md) · [Общий индекс](../index.md)

| Статья | Краткое описание | Источник |
| --- | --- | --- |
| [ЗапросSql — Программный тип XBSL: Std / Database / Sql](../queries/sqlquery-ru-81232e8a7d08.md) | *Базовые типы:* Объект | [Raw](../../raw/text-10.0/sqlquery-ru-81232e8a7d08-9b91c371269db6d5.md) |
| [ЗапросSqlБезВыборки — Программный тип XBSL: Std / Database / Sql](../queries/sqlquerywithoutselect-ru-7c15635cb95f.md) | Запрос, который не возвращает выборку и не является вызовом хранимой процедуры или блока. | [Raw](../../raw/text-10.0/sqlquerywithoutselect-ru-7c15635cb95f-5b612563c6a32602.md) |
| [ЗапросSqlВызовПроцедуры — Программный тип XBSL: Std / Database / Sql](../queries/sqlqueryprocedurecall-ru-f81cef4a20b9.md) | Предназначен для запросов, вызывающих хранимую процедуру или блок с out параметрами. | [Raw](../../raw/text-10.0/sqlqueryprocedurecall-ru-f81cef4a20b9-b25ba2e81b77a180.md) |
| [ЗапросSqlСВыборкой — Программный тип XBSL: Std / Database / Sql](../queries/sqlquerywithselect-ru-1d2ee8fe3d18.md) | Запрос, который возвращает выборку из базы. | [Raw](../../raw/text-10.0/sqlquerywithselect-ru-1d2ee8fe3d18-4e0b0e326589e41a.md) |
| [ИсключениеSql — Программный тип XBSL: Std / Database / Sql](sqlexception-ru-c108d8de1746.md) | Исключение, которое выбрасывается при ошибке доступа к базе данных при помощи механизмов Jdbc. | [Raw](../../raw/text-10.0/sqlexception-ru-c108d8de1746-3eb33aeef9ea603a.md) |
| [РезультатВыборкиSql — Программный тип XBSL: Std / Database / Sql](sqlselectresult-ru-b351439e205b.md) | *Базовые типы:* Закрываемое, Объект | [Raw](../../raw/text-10.0/sqlselectresult-ru-b351439e205b-81f0253522588e8c.md) |
| [РезультатВызоваПроцедурыSql — Программный тип XBSL: Std / Database / Sql](sqlprocedurecallresult-ru-32a7cafaceba.md) | Результат выполнения запроса, вызывающего процедуру. | [Raw](../../raw/text-10.0/sqlprocedurecallresult-ru-32a7cafaceba-d91a0ce3ddbe3e85.md) |
| [СоединениеSql — Программный тип XBSL: Std / Database / Sql](sqlconnection-ru-c5e86d40a6b0.md) | *Базовые типы:* Закрываемое, Объект | [Raw](../../raw/text-10.0/sqlconnection-ru-c5e86d40a6b0-60b5606e186cdd32.md) |
| [ТипДанныхSql — Программный тип XBSL: Std / Database / Sql](sqldatatype-ru-c79a407c2f77.md) | Типы данных параметров запросов. | [Raw](../../raw/text-10.0/sqldatatype-ru-c79a407c2f77-cf1e2ea1b42522b8.md) |
| [ТранзакцияSql — Программный тип XBSL: Std / Database / Sql](sqltransaction-ru-1145231f0cfe.md) | *Базовые типы:* Закрываемое, Контекст, Объект | [Raw](../../raw/text-10.0/sqltransaction-ru-1145231f0cfe-7f7990a0dc35988b.md) |
