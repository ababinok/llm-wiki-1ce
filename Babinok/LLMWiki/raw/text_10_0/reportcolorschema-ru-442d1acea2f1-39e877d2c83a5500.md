# ЦветоваяСхемаОтчета

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/ReportColorSchema_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/ReportColorSchema_ru/index.html
> SHA256: 066d3b3c5bb41d27e38275a7c975aa5cd14c0567ca2b48536f833929b72228a8
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Содержит цвета, которые могут использоваться в [отчете](../../wiki/project/create-report-b99954f7595c.md) и [панели отчетов](../../wiki/project/create-report-panel-87c9cc72c0f5.md) для настройки цветов таблиц, диаграмм и т. д.

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
Представление: Строка
```

Представление цветовой схемы отчета.

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

#### Цвета

```yaml
Цвета: АбсолютныйЦвет[]
```

Список абсолютных цветов, применяющихся в отчете.

---

#### ЦветаТемнойТемы

```yaml
ЦветаТемнойТемы: АбсолютныйЦвет[]
```

Список абсолютных цветов, применяющихся в отчете для темной темы. Если он не заполен, то используется список цветов из свойства [Цвета](../../wiki/project/reportcolorschema-ru-442d1acea2f1.md).

---
