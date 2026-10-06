# ГлобальноеКлиентскоеСобытие

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/GlobalClientEvent/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/GlobalClientEvent/index.html
> SHA256: b7e65342ff86513b113b534fa3e92c2d952232a02acbf5b301e38cc6186fa76b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Описывает одно [глобальное событие](../../wiki/project/global-client-event-a95b777ebee1.md) (на уровне подсистемы или пакета). Такое событие не связано с экземпляром какого-либо типа.

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
Параметры: ПараметрГлобальногоКлиентскогоСобытия[]
```

Массив описаний параметров данного события.

---
