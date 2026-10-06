# КлиентSoapСервиса

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [soapserviceclient-ru-3fc2a15878af-f1e6a336445cf83b](../../raw/text-10.0/soapserviceclient-ru-3fc2a15878af-f1e6a336445cf83b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Элемент проекта.

Имена для поиска: `КлиентSoapСервиса`, `SoapServiceClient`, `Std::ProjectElements::SoapServiceClient`.

## Обзор

[Клиент SOAP-сервиса](soap-web-service-client-e79277c8f091.md) позволяет вызывать внешний Web (SOAP) сервис и удобно обрабатывать полученные ответы.

## Документированный контракт и примеры

[Клиент SOAP-сервиса](soap-web-service-client-e79277c8f091.md) позволяет вызывать внешний Web (SOAP) сервис и удобно обрабатывать полученные ответы.

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

[Видимость](../language/modular-development-80166cfecf93.md) элемента проекта:

- [ВПодсистеме](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден внутри одной подсистемы во всех пакетах (значение по умолчанию);
- [ВПроекте](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах одного проекта;
- [Глобально](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах всех проектов.

---

#### Импорт

```yaml
Импорт: ПространствоИмен[]
```

Список [импортированных пространств имен](../language/modular-development-80166cfecf93.md).

---

#### UrlПоУмолчанию

```yaml
UrlПоУмолчанию: Строка
```

URL, по которому выполняется запрос к SOAP-сервису.

Вы можете выполнять запросы по адресу, отличающемуся от **UrlПоУмолчанию**. В этом случае при [создании экземпляра](soap-web-service-client-e79277c8f091.md) типа [ИмяКлиентаSoapСервиса](soapserviceclientname-ru-9b679540c78e.md) в конструктор требуется передать объект **КлиентHttp** в качестве параметра.

---

#### ВерсияSoap

```yaml
ВерсияSoap: ВерсияSoap
```

Версия SOAP, используемая при формировании исходящих и интерпретации входящих SOAP-сообщений. Версия по умолчанию — SOAP 1.1.

---

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяКлиентаSoapСервиса}.ServiceFaultNameДетали — Порождаемый тип XBSL: SoapServiceClientName](soapserviceclientname-servicefaultnamedetail-ru-444db625c190.md)
- [{ИмяКлиентаSoapСервиса}.ServiceFaultName — Порождаемый тип XBSL: SoapServiceClientName](soapserviceclientname-servicefaultname-ru-1dd42a0e9d5b.md)
- [{ИмяКлиентаSoapСервиса}.ServiceStructureName — Порождаемый тип XBSL: SoapServiceClientName](soapserviceclientname-servicestructurename-ru-c45aa6248a9d.md)
- [{ИмяКлиентаSoapСервиса} — Порождаемый тип XBSL: SoapServiceClientName](soapserviceclientname-ru-9b679540c78e.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [КлиентSoapСервиса](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/SoapServiceClient_ru/).
