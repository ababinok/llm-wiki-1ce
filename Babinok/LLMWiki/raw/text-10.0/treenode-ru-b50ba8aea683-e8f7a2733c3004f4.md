# УзелДерева

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/DataSources/Tree/TreeNode_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/DataSources/Tree/TreeNode_ru/index.html
> SHA256: ab40f988f4cd2906a2e358f26637a220e18c14b7efa66a4201db3d60df9decd2
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::ИсточникиДанных::Дерево::УзелДерева<ТипУзлов,ТипЭлементов>` `Доступность: КлиентИСервер`

ТипУзлов: тип данных элементов-узлов ТипЭлементов: тип данных элементов, не являющихся узлами дерева(не имеющих дочерних элементов)

Базовый класс узлов дерева. Используется в [ИсточникДанныхДерево](../../wiki/interface/treedatasource-ru-367f34c33419.md) как тип элементов-узлов.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [УзелДереваПодгружаемый<ТипУзлов, ТипЭлементов>](../../wiki/interface/loadabletreenode-ru-ee20b1cb5057.md)

*Дочерние типы:* [УзелДереваСДанными](../../wiki/interface/treenodewithdata-ru-c4d692cff100.md), [ЭлементДиаграммыГанта](../../wiki/interface/ganttchartitem-ru-952871018e2b.md)

---

## Свойства

### ДочерниеЭлементы

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
ДочерниеЭлементы: ЧитаемыйМассив<ТипЭлементов|ТипУзлов>
```

Дочерние элементы данного узла

Переопределение: [ДочерниеЭлементы](../../wiki/interface/treenode-ru-b50ba8aea683.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
