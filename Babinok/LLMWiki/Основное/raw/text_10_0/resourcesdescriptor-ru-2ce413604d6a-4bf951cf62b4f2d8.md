# Ресурсы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/ResourcesDescriptor_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/ResourcesDescriptor_ru/index.html
> SHA256: 1364e55278c339047d8039fe3a80eb9194c547b1218036a5101fd91c6e31f843
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Произвольные файлы, которые требуются для работы [приложения](../../wiki/project/application-89b2d17b70b1.md). В каждой [подсистеме](../../wiki/project/subsystem-ed73967ead84.md) и в каждом [пакете](../../wiki/project/package-8893e32778ef.md) может быть собственный набор ресурсов со своей [областью видимости](../../wiki/project/scope-2cbe4706e1b7.md). Все файлы хранятся в каталоге **Ресурсы**, внутри которого по умолчанию создается элемент **Описание ресурсов**. С помощью его свойства **ОбластьВидимости** можно ограничить область видимости ресурсов.

---

## Свойства

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
