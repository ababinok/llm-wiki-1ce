# МаршрутизаторПоСодержимому

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/Std/Schema/Nodes/ContentBasedRouter_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/IntegrationProcessSchema/Std/Schema/Nodes/ContentBasedRouter_ru/index.html
> SHA256: 2b036e4fc3e25f484f076fb629c0a5d934f250e5726ff2223f0ea738f3d51eac
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Узел этого вида позволяет определить, в какие узлы из тех, что идут непосредственно за данным узлом, должны попасть сообщения.

---

## Свойства

### Стандартные

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### Описание

```yaml
Описание: Строка
```

Описание элемента.

---

### События

#### ВыборПолучателей

```yaml
ВыборПолучателей: Строка
```

Обработчик, который позволяет определить получателей сообщения. Возвращает набор узлов, в которые должно быть передано сообщение.

---

#### ОбновлениеМетрик

```yaml
ОбновлениеМетрик: Строка
```

Обработчик, внутри которого можно обновлять метрики, добавленные в проект разработчиком.

---
