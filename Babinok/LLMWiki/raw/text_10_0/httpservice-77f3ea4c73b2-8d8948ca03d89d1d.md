# HttpСервис

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/HttpService/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/HttpService/index.html
> SHA256: 0870c3da86966d6285ac51c41d1e3e276eb5ee0f631460605e8b756f4a3963b4
> SnapshotCreated: 2026-10-05
> Rendition: verified text

[Реализует](../../wiki/integration/http-service-element-20a693318e85.md) функциональность поставщика HTTP-сервиса. Позволяет создать программный интерфейс приложения (API), который будет доступен с помощью HTTP-запросов.

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

#### КорневойUrl

```yaml
КорневойUrl: Строка
```

Корневой URL сервиса.

---

#### КонтрольДоступа

```yaml
КонтрольДоступа: 
    Разрешения: 
        ПоУмолчанию: КонтрольДоступа
        Вызов: КонтрольДоступа
```

Содержит [настройки прав доступа](../../wiki/security/http-service-access-permissions-0998f45d9af8.md).

<details>
<summary>**Свойства**</summary>

##### Разрешения

Набор разрешений на выполнение основных операций с HTTP-сервисом.

<details>
<summary>**Свойства**</summary>

##### ПоУмолчанию

Задает все разрешения элемента проекта, которые не указаны явно.

##### Вызов

Набор разрешений вызова всего сервиса в целом.

</details>

</details>

---

## Дочерние элеметы

#### ШаблоныUrl

```yaml
ШаблоныUrl: ШаблонUrl[]
```

Коллекция [шаблонов URL](../../wiki/project/url-template-selection-4bfb8d21eb1e.md), которая позволяет выбрать обработчик для заданного пути к ресурсу и предоставить удобный способ работы с параметрами, включенными в путь к ресурсу.

---
