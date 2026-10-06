# {ИмяКлиентаSoapСервиса}.ServiceFaultName

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [soapserviceclientname-servicefaultname-ru-1dd42a0e9d5b-c2ca20a551077280](../../raw/text-10.0/soapserviceclientname-servicefaultname-ru-1dd42a0e9d5b-c2ca20a551077280.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: SoapServiceClientName.

Имена для поиска: `{ИмяКлиентаSoapСервиса}.ServiceFaultName`, `SoapServiceClientName.ServiceFaultName`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяКлиентаSoapСервиса}.ServiceFaultName`, `DeveloperName::ProjectName::SubsystemName::SoapServiceClientName.ServiceFaultName`.

## Обзор

Исключение, генерируемое для ошибки SOAP-сервиса по ее описанию в WSDL (секция `fault`).

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяКлиентаSoapСервиса}.ServiceFaultName` `Доступность: Сервер`

Исключение, генерируемое для ошибки SOAP-сервиса по ее описанию в WSDL (секция `fault`). Базовый тип: [ИсключениеВызоваSoapСервиса](soapservicecallexception-ru-928205adb79d.md).

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../stdlib/exception-ru-ed2632721976.md), [ИсключениеВызоваSoapСервиса](soapservicecallexception-ru-928205adb79d.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Свойства

### Детали

`Доступность: Сервер` `ТолькоЧтение`

```
Детали: {ИмяКлиентаSoapСервиса}.ServiceFaultNameДетали
```

Детали ошибки

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

## Список унаследованных событий

### Исключение

[Ид](../stdlib/exception-ru-ed2632721976.md), [Описание](../stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../stdlib/exception-ru-ed2632721976.md), [Причина](../stdlib/exception-ru-ed2632721976.md)

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [КлиентSoapСервиса — Элемент проекта](soapserviceclient-ru-3fc2a15878af.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [{ИмяКлиентаSoapСервиса}.ServiceFaultName](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/SoapServiceClientName.ServiceFaultName_ru/).
