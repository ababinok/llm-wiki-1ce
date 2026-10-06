# СхемаАутентификацииHttp

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [httpauthenticationschema-ru-63e3be7b7b07-12c91ded912aea97](../../raw/text-10.0/httpauthenticationschema-ru-63e3be7b7b07-12c91ded912aea97.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Http.

Имена для поиска: `СхемаАутентификацииHttp`, `HttpAuthenticationSchema`, `Стд::Http::СхемаАутентификацииHttp`, `Std::Http::HttpAuthenticationSchema`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Перечисление](../stdlib/enum-ru-a7a357b96b4c.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md)

## Документированный контракт и примеры

`Стд::Http::СхемаАутентификацииHttp` `Доступность: КлиентИСервер`

Схема HTTP-аутентификации.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md), [Перечисление](../stdlib/enum-ru-a7a357b96b4c.md), [Представляемое](../stdlib/presentable-ru-fc7455a0880f.md)

---

## Элементы

## Свойства

### Базовая

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Базовая
```

Схема аутентифкации, при которой имя пользователя и пароль передаются в заголовке Authorization в виде base64-строки. При использовании HTTPS-протокола, является относительно безопасной.

---

### Ос

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Ос
```

Схема позволяющая использовать NTLM-аутентификацию Windows.

---

## Список унаследованных методов

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

### Перечисление

[ВСтроку](../stdlib/enum-ru-a7a357b96b4c.md)

[Представление](../stdlib/enum-ru-a7a357b96b4c.md)

### Представляемое

## Список унаследованных свойств

### Перечисление

[Индекс](../stdlib/enum-ru-a7a357b96b4c.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Стд::Http — Пространство имён XBSL: Std](../integration/http-7a0208cd0480.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [СхемаАутентификацииHttp](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Http/HttpAuthenticationSchema_ru/).
