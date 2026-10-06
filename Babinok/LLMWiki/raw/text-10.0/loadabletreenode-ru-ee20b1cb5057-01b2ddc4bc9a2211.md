# УзелДереваПодгружаемый

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/DataSources/Tree/LoadableTreeNode_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/DataSources/Tree/LoadableTreeNode_ru/index.html
> SHA256: 600fb712772b19bd92f64eb041ef2a9ef3dc31cd4033572de965c52e1c961fa0
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ИсточникиДанных::Дерево::УзелДереваПодгружаемый<ТипУзлов,ТипЭлементов>` `Доступность: КлиентИСервер`

ТипУзлов: тип данных элементов-узлов ТипЭлементов: тип данных элементов, не являющихся узлами дерева(не имеющих дочерних элементов)

Базовый класс узлов дерева с динамической загрузкой дочерних элементов. Используется в [ИсточникДанныхДеревоПодгружаемый](../../wiki/interface/loadabletreedatasource-ru-feb2e5334aa8.md) как тип элементов-узлов.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [СтрокаУзлаДинамическогоСписка](../../wiki/interface/dynamiclistnoderow-ru-ec60c33112b7.md), [УзелДерева](../../wiki/interface/treenode-ru-b50ba8aea683.md), [УзелДереваСДаннымиПодгружаемый](../../wiki/interface/loadabletreenodewithdata-ru-99f8911a6722.md), [ЭлементОрганиграммы](../../wiki/interface/organigramitem-ru-7daa0e5e236a.md)

---

## Свойства

### ДочерниеЭлементы

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ДочерниеЭлементы: ЧитаемыйМассив<ТипЭлементов|ТипУзлов>?
```

Дочерние элементы данного узла. Если равно Неопределено, система считает, что дочерние элементы ещё не загружены.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
