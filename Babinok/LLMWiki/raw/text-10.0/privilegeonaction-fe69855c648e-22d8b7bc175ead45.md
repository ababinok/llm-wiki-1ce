# ПравоНаДействие

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/PrivilegeOnAction/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/PrivilegeOnAction/index.html
> SHA256: c9361253be34be1a4d8fad5d2d8cbd69047cd1754e25c99654930d4d850001a8
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Элемент проекта [ПравоНаДействие](../../wiki/project/privilege-on-action-e770fbcdbee4.md) описывает права на действия. Может содержать параметры.

Право на действие не привязано к конкретной сущности. Его наличие проверяется вручную разработчиком.

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

Представление элемента.

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
Параметры: ПараметрКлассаКлючейДоступа|Владелец[]
```

Параметры ключа доступа.

---
