# ПрограммныйИсточник

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/Std/Schema/Nodes/ProgrammaticSource_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/IntegrationProcessSchema/Std/Schema/Nodes/ProgrammaticSource_ru/index.html
> SHA256: 89239c5891d37f47fb961abada00e3d2d890906d388e99a7b35f5748e68474f4
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Узел вида **ПрограммныйИсточник** предназначен для программной отправки сообщения в процесс интеграции.

Процесс интеграции может содержать 0, 1 или несколько узлов программных источников сообщений.

Для программной отправки сообщения требуется:

- создать сообщение,
- отправить сообщение в процесс интеграции методом
  
  [ОтправитьСообщениеВУзлы](../../wiki/integration/integrationprocess-ru-136570064b69.md)
  
  .

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

#### ОбновлениеМетрик

```yaml
ОбновлениеМетрик: Строка
```

Обработчик, внутри которого можно обновлять метрики, добавленные в проект разработчиком.

---
