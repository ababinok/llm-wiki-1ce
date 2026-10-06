# Регистратор

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/InformationRegister/Attributes/Recorder_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/InformationRegister/Attributes/Recorder_ru/index.html
> SHA256: cddcfe5da332024422c30eafff4de1b416a7a632a732d1344e1b1213075210c2
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Обязательный стандартный реквизит, содержащий ссылки на документы, которые являются регистраторами для [подчиненного регистра сведений](../../wiki/data/subordinated-information-register-7e7da053300b.md).

---

## Свойства

#### Тип

```yaml
Тип: Тип[]
```

Тип реквизита. Должен содержать ссылки на элементы проекта вида [Документ](../../wiki/data/document-element-0c6b898a8b13.md).

---

#### Представление

```yaml
Представление: Строка|СсылкаНаЛокализованнуюСтроку
```

Представление реквизита.

---

#### ВажностьПриОтображении

```yaml
ВажностьПриОтображении: ВажностьПриОтображении
```

Важность реквизита при отображении в интерфейсе приложения. Задается значением перечисления [ВажностьПриОтображении](../../wiki/project/displayimportance-ru-469c555fd91c.md). Значение по умолчанию — [Обычная](../../wiki/project/displayimportance-ru-469c555fd91c.md).

---

#### ЗаполнятьПриКопировании

```yaml
ЗаполнятьПриКопировании: Булево
```

Свойство определяет, заполнять ли элемент при копировании.

---

#### ИспользоватьВПолнотекстовомПоиске

```yaml
ИспользоватьВПолнотекстовомПоиске: Булево
```

Признак индексирования значений реквизита для использования в [полнотекстовом поиске](../../wiki/project/full-text-search-99b98022003a.md).

---
