# Стд::SoapСервисы

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/SoapServices/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/SoapServices/index.html
> SHA256: 44c8767f2758f3526a60302008baaa35d8618569b6dc43a34a0c931a5df7592d
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Типы для работы с SOAP-сервисами.

# Типы

## [SoapСервис](../../wiki/integration/soapservice-ru-fe39d75e5abe.md)

`Стд::SoapСервисы::SoapСервис` `Доступность: Сервер`

Базовый тип Soap-сервиса. Для каждого элемента проекта вида `Soap Сервис` создается тип, производный от данного типа.

---

## [SoapСервисПраво](../../wiki/integration/soapserviceprivilege-ru-17102d48afb8.md)

`Стд::SoapСервисы::SoapСервисПраво` `Доступность: КлиентИСервер`

Право Soap-сервиса.

---

## [ДанныеЭлементаSoap](../../wiki/integration/soapelementdata-ru-addbd5826e64.md)

`Стд::SoapСервисы::ДанныеЭлементаSoap` `Доступность: Сервер`

Данные элемента SOAP-запроса или SOAP-ответа [ЭлементSoap](../../wiki/integration/soapelement-ru-2e11ea4af034.md), не определенного в XSD-схеме.

---

## [ЗаписьSoap_1_1](../../wiki/integration/soapwriter-1-1-ru-58916d6c8a6f.md)

`Стд::SoapСервисы::ЗаписьSoap_1_1` `Доступность: Сервер`

Позволяет выполнять запись Soap-заголовков в обработчике `НастроитьЗаголовкиSoap{ИмяМетодаСервиса}` для клиента сервиса [SOAP версии 1.1](https://www.w3.org/TR/soap11/).

---

## [ЗаписьSoap_1_2](../../wiki/integration/soapwriter-1-2-ru-30259547d0dd.md)

`Стд::SoapСервисы::ЗаписьSoap_1_2` `Доступность: Сервер`

Позволяет выполнять запись Soap-заголовков в обработчике `НастроитьЗаголовкиSoap{ИмяМетодаСервиса}` для клиента сервиса [SOAP версии 1.2](https://www.w3.org/TR/soap12/).

---

## [ИсключениеВызоваSoapСервиса](../../wiki/integration/soapservicecallexception-ru-928205adb79d.md)

`Стд::SoapСервисы::ИсключениеВызоваSoapСервиса` `Доступность: Сервер`

Исключение, выбрасываемое при ошибке вызова метода SOAP-сервиса.

---

## [ОтветSoap](../../wiki/integration/soapresponse-ru-1c747b82e956.md)

`Стд::SoapСервисы::ОтветSoap` `Доступность: Сервер`

Ответ операции Soap-сервиса.

---

## [ОтветФункцииSoap](../../wiki/integration/soapfunctionresponse-ru-91da265e3b85.md)

`Стд::SoapСервисы::ОтветФункцииSoap<ТипРезультата>` `Доступность: Сервер`

ТипРезультата: тип результата операции Soap-сервиса.

Ответ операции Soap-сервиса с возвращаемым значением.

---

## [РольSoap](../../wiki/integration/soaprole-ru-cbb4332588e7.md)

`Стд::SoapСервисы::РольSoap` `Доступность: КлиентИСервер`

Перечисление, в котором элементы соответствуют [особым ролям SOAP версии 1.2](https://www.w3.org/TR/soap12-part1/#soaproles).

---

## [ЭлементSoap](../../wiki/integration/soapelement-ru-2e11ea4af034.md)

`Стд::SoapСервисы::ЭлементSoap` `Доступность: Сервер`

Элемент SOAP-запроса или SOAP-ответа, не определенный в XSD-схеме.

---
