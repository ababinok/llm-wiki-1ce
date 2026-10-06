# Выражения и операторы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/expressions-and-statements/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/expressions-and-statements/index.html
> SHA256: 36ce9561108e31be272e105a0f6493625928a0291b07d5e7ab8d31987fdd6c2b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

**Выражение** — это конструкция, предназначенная для фильтрации данных и выполнения вычислений. Выражение является комбинацией значений, операторов и функций и возвращает одно результирующее значение.

Выражения включают:

- Функции языка запросов:
  
  [`ВСтроку() | Представление()`](../../wiki/queries/convert-to-string-in-query-language-6ba1d1ebcf45.md)
  
  ,
  
  [`НачинаетсяС()`](../../wiki/project/starts-with-function-a56f3d328107.md)
  
  ,
  
  [`ЗаканчиваетсяНа()`](../../wiki/project/ends-with-function-8439efb7c7f3.md)
  
  ,
  
  [`Содержит()`](../../wiki/project/contains-24e2d0f0ef06.md)
  
  ,
  
  [`Подстрока()`](../../wiki/project/substring-function-af81f8bdfb50.md)
  
  ,
  
  [`ПолноеСовпадение()`](../../wiki/project/full-match-function-b14bbd9c192f.md)
  
  ,
  
  [`ЗаменитьNull()`](../../wiki/project/replace-null-function-5640be6823d2.md)
  
  ,
  
  [`ПолучитьТип()`](../../wiki/language/get-type-function-5fc1f4ab9022.md)
  
  ,
  
  [`ПервыйНеNull()`](../../wiki/project/first-not-null-function-7ac4040e7ae0.md)
  
  и
  
  [`Ууид()`](../../wiki/project/uuid-function-31a65de81142.md)
  
  .
- Агрегатные функции, которые выполняют вычисления над набором строк или множеством значений в столбце:
  
  [`СУММА`](../../wiki/project/sum-function-573661832e3d.md)
  
  ,
  
  [`СРЕДНЕЕ`](../../wiki/project/average-function-e72d3c8b614b.md)
  
  ,
  
  [`МАКСИМУМ`](../../wiki/project/maximum-function-775cdfef05db.md)
  
  ,
  
  [`МИНИМУМ`](../../wiki/project/minimum-function-febe8e3edf84.md)
  
  ,
  
  [`КОЛИЧЕСТВО`](../../wiki/project/count-function-6de4a6dd5b96.md)
  
  .
- Алгебраические и тригонометрические функции (
  
  [подробнее](../../wiki/project/math-and-trigonometric-functions-3f4d617eaae8.md)
  
  ).
- Арифметические операции (
  
  [подробнее](../../wiki/queries/arithmetic-operations-in-query-language-82549fa924ca.md)
  
  ).
- Логические и булевы операции (
  
  [подробнее](../../wiki/queries/logical-and-boolean-operations-in-query-language-9dc1f24038ae.md)
  
  ).
- Выражения языка запросов:
  
  [`В`](../../wiki/project/in-expression-4ca0af667609.md)
  
  ,
  
  [`В ИЕРАРХИИ`](../../wiki/project/in-hierarchy-expression-e8dc73bcd687.md)
  
  ,
  
  [`ВЫБОР`](../../wiki/project/case-expression-2994dba9cd16.md)
  
  ,
  
  [`ВЫРАЗИТЬ`](../../wiki/language/cast-expression-496e917073d0.md)
  
  ,
  
  [`ЕСТЬ NULL`](../../wiki/project/is-null-expression-70c78665b1f8.md)
  
  ,
  
  [`МЕЖДУ`](../../wiki/project/between-expression-2bb93e3361cc.md)
  
  ,
  
  [`ОТЛИЧАЕТСЯ ОТ`](../../wiki/project/is-distinct-from-expression-86df4534b06c.md)
  
  ,
  
  [`ПОДОБНО`](../../wiki/project/like-expression-a2ee0738bbc9.md)
  
  ,
  
  [`СУЩЕСТВУЕТ`](../../wiki/project/exists-expression-96fd1b953866.md)
  
  .
- Выражения получения значений:
  
  [`.`](../../wiki/queries/get-attribute-in-query-42c2e715ec22.md)
  
  и
  
  [`&`](../../wiki/queries/get-query-parameter-value-2f5aca098829.md)
  
  .

**Операторы** — это базовые команды, управляющие действиями с данными. Они определяют структуру запроса и тип выполняемых операций: выборку данных, изменение записей, фильтрацию или объединение источников. К ним относятся ключевые инструкции, задающие общую логику работы с информацией (например, выбор полей, условия обработки или способ соединения данных).

| Оператор | Англ. | Подробнее |
| --- | --- | --- |
| `ВСТАВИТЬ` | `INSERT` | [Оператор ВСТАВИТЬ](../../wiki/project/insert-statement-ba077d6b6305.md) |
| `ВЫБРАТЬ` | `SELECT` | [Оператор ВЫБРАТЬ](../../wiki/project/select-statement-0fef6f15002c.md) |
| `ИЗМЕНИТЬ` | `UPDATE` | [Оператор ИЗМЕНИТЬ](../../wiki/project/update-statement-7deb16c5d919.md) |
| `ОБРЕЗАТЬ` | `TRUNCATE` | [Оператор ОБРЕЗАТЬ](../../wiki/project/truncate-statement-c32b63f4ab3a.md) |
| `СОЗДАТЬ ВРЕМЕННУЮ ТАБЛИЦУ` | `CREATE TEMPORARY TABLE` | [Оператор СОЗДАТЬ ВРЕМЕННУЮ ТАБЛИЦУ](../../wiki/project/create-temporary-table-statement-cdc840b8b1e3.md) |
| `СОЗДАТЬ ИНДЕКС` | `CREATE INDEX` | [Оператор СОЗДАТЬ ИНДЕКС](../../wiki/project/create-temporary-table-statement-cdc840b8b1e3.md) |
| `УДАЛИТЬ` | `DELETE` | [Оператор УДАЛИТЬ](../../wiki/project/delete-statement-e6de4fd70bea.md) |
| `УНИЧТОЖИТЬ` | `DROP` | [Оператор УНИЧТОЖИТЬ](../../wiki/project/drop-statement-2e25a487bf09.md) |

> [!NOTE] примечание
> Подробная информация о выражениях и операторах, доступных в языке запросов, приведена в соответствующем разделе [Справочной информации](../../wiki/queries/xbql-cd527e12e781.md).


Примечание. [Описание иллюстрации](../figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)
