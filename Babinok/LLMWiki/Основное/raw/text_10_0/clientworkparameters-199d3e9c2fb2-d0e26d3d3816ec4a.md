# ПараметрыРаботыКлиента

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/ClientWorkParameters/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/ClientWorkParameters/index.html
> SHA256: b50c50d6446d6dc2bd3f770da3b49fe18e946987761a8f1b6380a122b3d2b2b5
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Описывает произвольный набор свойств, которые инициализируются на сервере при открытии приложения. На клиенте можно получить доступ к этим свойствам.

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

## Дочерние элеметы

#### Параметры

```yaml
Параметры: ПараметрПараметровРаботыКлиента[]
```

Содержит описание параметров.

---
