# Параметр

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/Std/Schema/Parameters/Parameter_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/IntegrationProcessSchema/Std/Schema/Parameters/Parameter_ru/index.html
> SHA256: 7c2af88936f01aa71609237a528c2b5ea96953d1593c0597fdca8ef88f123cb2
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Параметр процесса интеграции. Используется, чтобы задать или переопределить свойства узлов процесса интеграции во время исполнения приложения.

Обращение к параметру процесса интеграции выполняется с помощью ключевого слова **Параметры**. Например, если у процесса интеграции есть параметр **КорневойКаталог** типа `Строка`, то в узле вида [ФайлНазначение](../../wiki/integration/filedestination-ru-be5b795b27a8.md) можно задать свойство **Каталог** не с абсолютным значением, а относительно этого параметра: `%{Параметры.КорневойКаталог}/Каталог1`.

Чтобы новые значения параметров применились, нужно перезапустить процесс интеграции.

---

## См. также

- [Параметры процесса интеграции](../../wiki/integration/computable-properties-4e2a3d4fac9d.md)
- [Создание параметров процесс интеграции](../../wiki/integration/integration-process-parameters-cecc1db499d5.md)
- [Задание значений параметров процесса интеграции](../../wiki/integration/specify-integration-process-properties-eac1f57c7e07.md)

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### Тип

```yaml
Тип: Тип<Булево|Число|Строка|Длительность>
```

Тип параметра.

---

#### Значение

```yaml
Значение: Объект
```

Значение параметра.

---
