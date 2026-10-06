# ХранимаяСтруктура

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/StorableStructure/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/StorableStructure/index.html
> SHA256: 0539add82386ba3b46c732c971103eff2184ffba137432f696dfa97ffdf2bb93
> SnapshotCreated: 2026-10-05
> Rendition: verified text

**ХранимаяСтруктура** — это [Структура](../../wiki/project/structure-6a8548d613f3.md), которая может использоваться как тип реквизита или тип измерения (ресурса, реквизита) элементов проекта [Справочник](../../wiki/data/catalog-e0da7d4e8e72.md) и [РегистрСведений](../../wiki/data/informationregister-ru-d15b0965bc15.md) для хранения данных в базе данных. Имеет следующие ограничения:

- окружение только
  
  [КлиентИСервер](../../wiki/project/environmentkind-ru-8bb797e2f7cc.md)
  
  ;
- поля могут быть только таких типов, для которых обеспечивается хранение в базе данных;
- две структуры не могут иметь поля, ссылающиеся друг на друга.

**ХранимуюСтруктуру** можно использовать как тип параметра и как тип результата [запланированного задания](../../wiki/project/scheduled-job-project-element-e47ed37b89ab.md) и в [полнотекстовом поиске](../../wiki/project/full-text-search-99b98022003a.md).

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### ОбластьВидимости

```yaml
ОбластьВидимости: ОбластьВидимости
```

[Видимость](../../wiki/language/modular-development-80166cfecf93.md) элемента проекта:

- [ВПодсистеме](../../wiki/project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден внутри одной подсистемы во всех пакетах (значение по умолчанию);
- [ВПроекте](../../wiki/project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах одного проекта;
- [Глобально](../../wiki/project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах всех проектов.

---

#### Импорт

```yaml
Импорт: ПространствоИмен[]
```

Список [импортированных пространств имен](../../wiki/language/modular-development-80166cfecf93.md).

---

#### НастройкиТипа

```yaml
НастройкиТипа: 
    Контракты: Строка[]
    Аннотации: Аннотация[]
```

Имена [контрактов типа](../../wiki/language/type-contract-ab9f0932850d.md), которые реализует структура, и [аннотации](../../wiki/language/annotations-dcff696b460d.md).

<details>
<summary>**Свойства**</summary>

##### Контракты

Имена [контрактов типа](../../wiki/language/type-contract-ab9f0932850d.md), которые реализует структура.

##### Аннотации

[Аннотации](../../wiki/language/annotations-dcff696b460d.md) структуры.

</details>

---

## Дочерние элеметы

#### Поля

```yaml
Поля: ПолеХранимойСтруктуры[]
```

Список полей структуры.

---
