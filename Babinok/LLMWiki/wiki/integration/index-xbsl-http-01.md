# XBSL: Std::Http

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [url-ru-3532308ec0d3-7790f5db390661ad](../../raw/text-10.0/url-ru-3532308ec0d3-7790f5db390661ad.md); [httpauthentication-ru-c477624f92ab-8d1a067c8d98d16a](../../raw/text-10.0/httpauthentication-ru-c477624f92ab-8d1a067c8d98d16a.md); [httpheaders-ru-6e1622bd347e-8c8826a993aecab5](../../raw/text-10.0/httpheaders-ru-6e1622bd347e-8c8826a993aecab5.md); [httprequest-ru-b138f7d5f696-111efe550932e33d](../../raw/text-10.0/httprequest-ru-b138f7d5f696-111efe550932e33d.md); [internetproxy-ru-4726d30aa885-bc84279c02cbc38b](../../raw/text-10.0/internetproxy-ru-4726d30aa885-bc84279c02cbc38b.md); [httpexception-ru-2140341cd0ec-27b4d5469a59de7d](../../raw/text-10.0/httpexception-ru-2140341cd0ec-27b4d5469a59de7d.md); [httpclient-ru-fc35d11b0b5c-225568ec91e9d235](../../raw/text-10.0/httpclient-ru-fc35d11b0b5c-225568ec91e9d235.md); [httpcontext-ru-6de81d9dbfc4-8cca0aa0c86ec297](../../raw/text-10.0/httpcontext-ru-6de81d9dbfc4-8cca0aa0c86ec297.md); [httpresponse-ru-8fa5b68112a5-a877ad51cd0cc54d](../../raw/text-10.0/httpresponse-ru-8fa5b68112a5-a877ad51cd0cc54d.md); [urlparameters-ru-86c195442542-1edc6ed84d687b50](../../raw/text-10.0/urlparameters-ru-86c195442542-1edc6ed84d687b50.md); [httpauthenticationschema-ru-63e3be7b7b07-12c91ded912aea97](../../raw/text-10.0/httpauthenticationschema-ru-63e3be7b7b07-12c91ded912aea97.md); [readablehttpheaders-ru-34dc6b2ca1c0-c48c8a1eceeffcde](../../raw/text-10.0/readablehttpheaders-ru-34dc6b2ca1c0-c48c8a1eceeffcde.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Оглавление раздела](overview.md) · [Общий индекс](../index.md)

| Статья | Краткое описание | Источник |
| --- | --- | --- |
| [Url — Программный тип XBSL: Std / Http](url-ru-3532308ec0d3.md) | Унифицированный адрес ресурса (`URL`-ссылка), представленный в виде объекта. | [Raw](../../raw/text-10.0/url-ru-3532308ec0d3-7790f5db390661ad.md) |
| [АутентификацияHttp — Программный тип XBSL: Std / Http](../security/httpauthentication-ru-c477624f92ab.md) | Данные аутентификации пользователя на сервере по протоколам Basic и NTLM. | [Raw](../../raw/text-10.0/httpauthentication-ru-c477624f92ab-8d1a067c8d98d16a.md) |
| [ЗаголовкиHttp — Программный тип XBSL: Std / Http](httpheaders-ru-6e1622bd347e.md) | Изменяемая коллекция заголовков HTTP. | [Raw](../../raw/text-10.0/httpheaders-ru-6e1622bd347e-8c8826a993aecab5.md) |
| [ЗапросHttp — Программный тип XBSL: Std / Http](httprequest-ru-b138f7d5f696.md) | Настраиваемый и исполняемый HTTP-запрос к серверу. | [Raw](../../raw/text-10.0/httprequest-ru-b138f7d5f696-111efe550932e33d.md) |
| [ИнтернетПрокси — Программный тип XBSL: Std / Http](internetproxy-ru-4726d30aa885.md) | *Базовые типы:* Объект | [Raw](../../raw/text-10.0/internetproxy-ru-4726d30aa885-bc84279c02cbc38b.md) |
| [ИсключениеHttp — Программный тип XBSL: Std / Http](httpexception-ru-2140341cd0ec.md) | Исключение, выбрасываемое при ошибках работы с внешними ресурсами по протоколу HTTP. | [Raw](../../raw/text-10.0/httpexception-ru-2140341cd0ec-27b4d5469a59de7d.md) |
| [КлиентHttp — Программный тип XBSL: Std / Http](httpclient-ru-fc35d11b0b5c.md) | Объект для работы с внешними ресурсами по протоколу HTTP. | [Raw](../../raw/text-10.0/httpclient-ru-fc35d11b0b5c-225568ec91e9d235.md) |
| [КонтекстHttp — Программный тип XBSL: Std / Http](httpcontext-ru-6de81d9dbfc4.md) | Состояние между выполнениями различных запросов к одному серверу. | [Raw](../../raw/text-10.0/httpcontext-ru-6de81d9dbfc4-8cca0aa0c86ec297.md) |
| [ОтветHttp — Программный тип XBSL: Std / Http](httpresponse-ru-8fa5b68112a5.md) | Ответ сервера на ЗапросHttp. | [Raw](../../raw/text-10.0/httpresponse-ru-8fa5b68112a5-a877ad51cd0cc54d.md) |
| [ПараметрыUrl — Программный тип XBSL: Std / Http](urlparameters-ru-86c195442542.md) | Коллекция параметров запроса. | [Raw](../../raw/text-10.0/urlparameters-ru-86c195442542-1edc6ed84d687b50.md) |
| [СхемаАутентификацииHttp — Программный тип XBSL: Std / Http](../security/httpauthenticationschema-ru-63e3be7b7b07.md) | *Базовые типы:* Объект, Перечисление, Представляемое | [Raw](../../raw/text-10.0/httpauthenticationschema-ru-63e3be7b7b07-12c91ded912aea97.md) |
| [ЧитаемыеЗаголовкиHttp — Программный тип XBSL: Std / Http](readablehttpheaders-ru-34dc6b2ca1c0.md) | Заголовки HTTP, доступные только для чтения. | [Raw](../../raw/text-10.0/readablehttpheaders-ru-34dc6b2ca1c0-c48c8a1eceeffcde.md) |
