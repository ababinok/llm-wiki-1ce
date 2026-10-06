# КомпонентИнтерфейса

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [interfacecomponent-d7fcdaf29819-da2a68d45eb07bbe](../../raw/text-10.0/interfacecomponent-d7fcdaf29819-da2a68d45eb07bbe.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Элемент проекта.

Имена для поиска: `КомпонентИнтерфейса`, `InterfaceComponent`, `Std::ProjectElements::InterfaceComponent`.

## Обзор

Элемент проекта, унаследованный от [системного компонента](system-component-6de48ba8685c.md).

## Документированный контракт и примеры

Элемент проекта, унаследованный от [системного компонента](system-component-6de48ba8685c.md). Получает от базового компонента все свойства, методы и события. Может также содержать собственные свойства и события, а также переопределенные базовые.

---

## См. также

- [Базовые компоненты интерфейса](system-and-interface-components-18287074edda.md)

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

[Видимость](../language/modular-development-80166cfecf93.md) элемента проекта:

- [ВПодсистеме](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден внутри одной подсистемы во всех пакетах (значение по умолчанию);
- [ВПроекте](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах одного проекта;
- [Глобально](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах всех проектов.

---

#### Импорт

```yaml
Импорт: ПространствоИмен[]
```

Список [импортированных пространств имен](../language/modular-development-80166cfecf93.md).

---

#### НастройкиТипа

```yaml
НастройкиТипа: 
    Контракты: Строка[]
```

Имена [контрактов типа](../language/type-contract-ab9f0932850d.md), которые реализует данный компонент.

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

[Контракт базового типа](../language/contract-4ba553680369.md).

---

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяКомпонента}.Компоненты — Порождаемый тип XBSL: ComponentName](componentname-components-ru-bb1111dec1f0.md)
- [{ИмяКомпонента}.Контекст — Порождаемый тип XBSL: ComponentName](componentname-context-ru-e40a3f370a75.md)
- [{ИмяКомпонента} — Порождаемый тип XBSL: ComponentName](componentname-ru-ca3fcf138ae8.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [КомпонентИнтерфейса](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/InterfaceComponent/).
