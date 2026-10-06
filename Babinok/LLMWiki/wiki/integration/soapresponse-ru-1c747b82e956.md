# ОтветSoap

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [soapresponse-ru-1c747b82e956-e8abb93b27c26176](../../raw/text-10.0/soapresponse-ru-1c747b82e956-e8abb93b27c26176.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / SoapServices.

Имена для поиска: `ОтветSoap`, `SoapResponse`, `Стд::SoapСервисы::ОтветSoap`, `Std::SoapServices::SoapResponse`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::SoapСервисы::ОтветSoap` `Доступность: Сервер`

Ответ операции Soap-сервиса.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ОтветФункцииSoap](soapfunctionresponse-ru-91da265e3b85.md)

---

## Свойства

### Заголовки

`Доступность: Сервер` `ТолькоЧтение`

```
Заголовки: Объект?
```

Soap-заголовки, прочитанные в обработчике `ОбработатьЗаголовкиSoap{ИмяМетодаСервиса}`. Если обработчика нет - `Неопределено`.

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::SoapСервисы — Пространство имён XBSL: Std](soapservices-55f8f2097e04.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ОтветSoap](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/SoapServices/SoapResponse_ru/).
