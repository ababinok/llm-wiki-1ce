# КлиентSoapСервиса

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/SoapServiceClient_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/SoapServiceClient_ru/index.html
> SHA256: 69d76d44d7d896bf418f261267a680ce3fe5b71c3d88fdfe568fcce6be031e00
> SnapshotCreated: 2026-10-05
> Rendition: verified text

[Клиент SOAP-сервиса](../../wiki/integration/soap-web-service-client-e79277c8f091.md) позволяет вызывать внешний Web (SOAP) сервис и удобно обрабатывать полученные ответы.

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

#### UrlПоУмолчанию

```yaml
UrlПоУмолчанию: Строка
```

URL, по которому выполняется запрос к SOAP-сервису.

Вы можете выполнять запросы по адресу, отличающемуся от **UrlПоУмолчанию**. В этом случае при [создании экземпляра](../../wiki/integration/soap-web-service-client-e79277c8f091.md) типа [ИмяКлиентаSoapСервиса](../../wiki/integration/soapserviceclientname-ru-9b679540c78e.md) в конструктор требуется передать объект **КлиентHttp** в качестве параметра.

---

#### ВерсияSoap

```yaml
ВерсияSoap: ВерсияSoap
```

Версия SOAP, используемая при формировании исходящих и интерпретации входящих SOAP-сообщений. Версия по умолчанию — SOAP 1.1.

---
