# ШаблонUrl

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [urltemplate-d1624a2e37c0-cdd9584987522677](../../raw/text-10.0/urltemplate-d1624a2e37c0-cdd9584987522677.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Свойство элемента проекта.

Владелец: HttpСервис / UrlTemplates.

Имена для поиска: `ШаблонUrl`, `UrlTemplate`, `Std::ProjectElements::HttpService::UrlTemplates::UrlTemplate`.

## Обзор

Экземпляр коллекции [ШаблоныUrl](httpservice-77f3ea4c73b2.md).

## Документированный контракт и примеры

Экземпляр коллекции [ШаблоныUrl](httpservice-77f3ea4c73b2.md).

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### Шаблон

```yaml
Шаблон: Строка
```

Имя шаблона.

---

#### ЛюбойМетод

```yaml
ЛюбойМетод: Строка
```

[Обработчик](method-ru-44c98737758b.md) по умолчанию.

---

#### КонтрольДоступа

```yaml
КонтрольДоступа: 
    Разрешения: 
        Вызов: КонтрольДоступа
    Обработчик: Строка
```

Содержит [настройки прав доступа](../security/http-service-access-permissions-0998f45d9af8.md) для данного URL-шаблона.

<details>
<summary>**Свойства**</summary>

##### Разрешения

Набор разрешений для элемента.

<details>
<summary>**Свойства**</summary>

##### Вызов

Режим контроля доступа для элемента.

</details>

##### Обработчик

Метод-обработчик, реализующий контроль доступа.

</details>

---

## Дочерние элеметы

#### Методы

```yaml
Методы: Метод[]
```

Коллекция [HTTP-методов](http-requests-2fbe5c3df089.md).

---

## See Also

- [Навигатор раздела](overview.md)
- [HttpСервис — Элемент проекта](httpservice-77f3ea4c73b2.md)
- [ШаблоныUrl — Свойство элемента проекта: HttpСервис](urltemplates-19463d935f4a.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ШаблонUrl](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/HttpService/UrlTemplates/UrlTemplate/).
