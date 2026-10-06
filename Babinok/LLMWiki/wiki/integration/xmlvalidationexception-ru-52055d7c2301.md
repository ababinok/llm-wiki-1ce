# ИсключениеПроверкиXml

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [xmlvalidationexception-ru-52055d7c2301-f3d5c5f6e5c5f67c](../../raw/text-10.0/xmlvalidationexception-ru-52055d7c2301-f3d5c5f6e5c5f67c.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Xml / Validation.

Имена для поиска: `ИсключениеПроверкиXml`, `XmlValidationException`, `Стд::Xml::Проверка::ИсключениеПроверкиXml`, `Std::Xml::Validation::XmlValidationException`.

## Обзор

Исключение, возникающее при проверке документа XML.

## Документированный контракт и примеры

`Стд::Xml::Проверка::ИсключениеПроверкиXml` `Доступность: Сервер`

Исключение, возникающее при проверке документа XML.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../stdlib/exception-ru-ed2632721976.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Свойства

### НомерКолонкиXml

`Доступность: Сервер` `ТолькоЧтение`

```
НомерКолонкиXml: Число?
```

Номер колонки, где произошла ошибка чтения.

---

### НомерСтрокиXml

`Доступность: Сервер` `ТолькоЧтение`

```
НомерСтрокиXml: Число?
```

Номер строки, где произошла ошибка чтения.

---

## Список унаследованных методов

### Исключение

[ВСтроку](../stdlib/exception-ru-ed2632721976.md)

[Информация](../stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../stdlib/exception-ru-ed2632721976.md), [Описание](../stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../stdlib/exception-ru-ed2632721976.md), [Причина](../stdlib/exception-ru-ed2632721976.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Xml::Проверка — Пространство имён XBSL: Std / Xml](validation-c6dbf204280f.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ИсключениеПроверкиXml](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Xml/Validation/XmlValidationException_ru/).
