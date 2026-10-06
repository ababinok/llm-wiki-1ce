# ОбщийМодуль

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/CommonModule_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/CommonModule_ru/index.html
> SHA256: 24b8e99506b681edabba6dc62a7ab2c031aba1c8b22dde4f12b622624474ed93
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Произвольный модуль, в котором обычно размещают переиспользуемые фрагменты кода — методы, вызываемые из разных частей проекта. Модуль порождает тип-одиночку, имя которого совпадает с именем модуля.

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

#### Окружение

```yaml
Окружение: ВидОкружения
```

[Окружение](../../wiki/project/context-60cdcec65127.md), в котором доступен элемент проекта: **Клиент**, **Сервер**, **КлиентИСервер**.

---

#### НастройкиТипа

```yaml
НастройкиТипа: 
    Контракты: Строка[]
```

[Контракты](../../wiki/project/contract-project-elements-4bb89cb1f89f.md), которые реализует общий модуль.

<details>
<summary>**Свойства**</summary>

##### Контракты

Имена [контрактов сервиса](../../wiki/project/service-contract-5b8423b5cca0.md), которые реализует данный модуль.

</details>

---
