# КолонкаЖурналаДанных

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/DataJournal/Columns/DataJournalColumn_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/DataJournal/Columns/DataJournalColumn_ru/index.html
> SHA256: 6ab45ac20523c6826089d96c3386fee77bdbd1e85ea552707546875bac23c870
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Колонка таблицы журнала данных. Соответствует полю таблицы в языке запросов.

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### Представление

```yaml
Представление: Строка|СсылкаНаЛокализованнуюСтроку
```

Представление реквизита.

---

#### Реквизиты

```yaml
Реквизиты: Строка[]
```

Перечень реквизитов вида `{ИмяСущности}.{ИмяРеквизита}`, значения которых должны храниться в одной колонке журнала. Не может быть пустым.

Сущности должны быть включены в [Состав](../../wiki/project/datajournal-3d0e7aa19753.md).

Если реквизит сущности не указан в свойстве, то соответствующая ему колонка будет хранить `Неопределено`. В таком случае будут заполнены только стандартные колонки.

---
