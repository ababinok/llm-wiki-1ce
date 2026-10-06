# Выражения и операторы

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [expressions-and-statements-eacedf9d00b5-9f5080c81dd70c4c](../../raw/text-10.0/expressions-and-statements-eacedf9d00b5-9f5080c81dd70c4c.md); [508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Выражения и операторы`, `expressions-and-statements`.

## Обзор

**Выражение** — это конструкция, предназначенная для фильтрации данных и выполнения вычислений.

## Документированный контракт и примеры

**Выражение** — это конструкция, предназначенная для фильтрации данных и выполнения вычислений. Выражение является комбинацией значений, операторов и функций и возвращает одно результирующее значение.

Выражения включают:

- Функции языка запросов:
  
  [`ВСтроку() | Представление()`](../queries/convert-to-string-in-query-language-6ba1d1ebcf45.md)
  
  ,
  
  [`НачинаетсяС()`](starts-with-function-a56f3d328107.md)
  
  ,
  
  [`ЗаканчиваетсяНа()`](ends-with-function-8439efb7c7f3.md)
  
  ,
  
  [`Содержит()`](contains-24e2d0f0ef06.md)
  
  ,
  
  [`Подстрока()`](substring-function-af81f8bdfb50.md)
  
  ,
  
  [`ПолноеСовпадение()`](full-match-function-b14bbd9c192f.md)
  
  ,
  
  [`ЗаменитьNull()`](replace-null-function-5640be6823d2.md)
  
  ,
  
  [`ПолучитьТип()`](../language/get-type-function-5fc1f4ab9022.md)
  
  ,
  
  [`ПервыйНеNull()`](first-not-null-function-7ac4040e7ae0.md)
  
  и
  
  [`Ууид()`](uuid-function-31a65de81142.md)
  
  .
- Агрегатные функции, которые выполняют вычисления над набором строк или множеством значений в столбце:
  
  [`СУММА`](sum-function-573661832e3d.md)
  
  ,
  
  [`СРЕДНЕЕ`](average-function-e72d3c8b614b.md)
  
  ,
  
  [`МАКСИМУМ`](maximum-function-775cdfef05db.md)
  
  ,
  
  [`МИНИМУМ`](minimum-function-febe8e3edf84.md)
  
  ,
  
  [`КОЛИЧЕСТВО`](count-function-6de4a6dd5b96.md)
  
  .
- Алгебраические и тригонометрические функции (
  
  [подробнее](math-and-trigonometric-functions-3f4d617eaae8.md)
  
  ).
- Арифметические операции (
  
  [подробнее](../queries/arithmetic-operations-in-query-language-82549fa924ca.md)
  
  ).
- Логические и булевы операции (
  
  [подробнее](../queries/logical-and-boolean-operations-in-query-language-9dc1f24038ae.md)
  
  ).
- Выражения языка запросов:
  
  [`В`](in-expression-4ca0af667609.md)
  
  ,
  
  [`В ИЕРАРХИИ`](in-hierarchy-expression-e8dc73bcd687.md)
  
  ,
  
  [`ВЫБОР`](case-expression-2994dba9cd16.md)
  
  ,
  
  [`ВЫРАЗИТЬ`](../language/cast-expression-496e917073d0.md)
  
  ,
  
  [`ЕСТЬ NULL`](is-null-expression-70c78665b1f8.md)
  
  ,
  
  [`МЕЖДУ`](between-expression-2bb93e3361cc.md)
  
  ,
  
  [`ОТЛИЧАЕТСЯ ОТ`](is-distinct-from-expression-86df4534b06c.md)
  
  ,
  
  [`ПОДОБНО`](like-expression-a2ee0738bbc9.md)
  
  ,
  
  [`СУЩЕСТВУЕТ`](exists-expression-96fd1b953866.md)
  
  .
- Выражения получения значений:
  
  [`.`](../queries/get-attribute-in-query-42c2e715ec22.md)
  
  и
  
  [`&`](../queries/get-query-parameter-value-2f5aca098829.md)
  
  .

**Операторы** — это базовые команды, управляющие действиями с данными. Они определяют структуру запроса и тип выполняемых операций: выборку данных, изменение записей, фильтрацию или объединение источников. К ним относятся ключевые инструкции, задающие общую логику работы с информацией (например, выбор полей, условия обработки или способ соединения данных).

| Оператор | Англ. | Подробнее |
| --- | --- | --- |
| `ВСТАВИТЬ` | `INSERT` | [Оператор ВСТАВИТЬ](insert-statement-ba077d6b6305.md) |
| `ВЫБРАТЬ` | `SELECT` | [Оператор ВЫБРАТЬ](select-statement-0fef6f15002c.md) |
| `ИЗМЕНИТЬ` | `UPDATE` | [Оператор ИЗМЕНИТЬ](update-statement-7deb16c5d919.md) |
| `ОБРЕЗАТЬ` | `TRUNCATE` | [Оператор ОБРЕЗАТЬ](truncate-statement-c32b63f4ab3a.md) |
| `СОЗДАТЬ ВРЕМЕННУЮ ТАБЛИЦУ` | `CREATE TEMPORARY TABLE` | [Оператор СОЗДАТЬ ВРЕМЕННУЮ ТАБЛИЦУ](create-temporary-table-statement-cdc840b8b1e3.md) |
| `СОЗДАТЬ ИНДЕКС` | `CREATE INDEX` | [Оператор СОЗДАТЬ ИНДЕКС](create-temporary-table-statement-cdc840b8b1e3.md) |
| `УДАЛИТЬ` | `DELETE` | [Оператор УДАЛИТЬ](delete-statement-e6de4fd70bea.md) |
| `УНИЧТОЖИТЬ` | `DROP` | [Оператор УНИЧТОЖИТЬ](drop-statement-2e25a487bf09.md) |

> [!NOTE] примечание
> Подробная информация о выражениях и операторах, доступных в языке запросов, приведена в соответствующем разделе [Справочной информации](../queries/xbql-cd527e12e781.md).


Примечание. [Описание иллюстрации](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Выражения и операторы](https://1cmycloud.com/console/help/element/10.0/docs/topics/expressions-and-statements/).
