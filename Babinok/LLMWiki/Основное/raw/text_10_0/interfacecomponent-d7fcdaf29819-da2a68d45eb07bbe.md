# КомпонентИнтерфейса

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/InterfaceComponent/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/InterfaceComponent/index.html
> SHA256: 10334c3d42d726938fb727de7dd5fd7d4bed343bfc007b83df804c548230c1aa
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Элемент проекта, унаследованный от [системного компонента](../../wiki/interface/system-component-6de48ba8685c.md). Получает от базового компонента все свойства, методы и события. Может также содержать собственные свойства и события, а также переопределенные базовые.

---

## См. также

- [Базовые компоненты интерфейса](../../wiki/interface/system-and-interface-components-18287074edda.md)

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
```

Имена [контрактов типа](../../wiki/language/type-contract-ab9f0932850d.md), которые реализует данный компонент.

<details>
<summary>**Свойства**</summary>

##### Контракты

Массив реализуемых контрактов.

</details>

---

## Дочерние элеметы

#### Свойства

```yaml
Свойства: Свойство[]
```

Свойства компонента интерфейса.

---

#### События

```yaml
События: Событие[]
```

События компонента интерфейса.

---

#### Наследует

```yaml
Наследует: Объект
```

[Контракт базового типа](../../wiki/language/contract-4ba553680369.md).

---
