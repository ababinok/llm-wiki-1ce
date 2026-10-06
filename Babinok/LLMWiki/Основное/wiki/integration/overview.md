# Интеграции и обмен данными

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [http-requests-2fbe5c3df089-9ac02208b677c265](../../raw/text-10.0/http-requests-2fbe5c3df089-9ac02208b677c265.md); [httpclient-ru-fc35d11b0b5c-225568ec91e9d235](../../raw/text-10.0/httpclient-ru-fc35d11b0b5c-225568ec91e9d235.md); [work-with-json-7cef407607e5-9dfff58948d1d868](../../raw/text-10.0/work-with-json-7cef407607e5-9dfff58948d1d868.md); [jsonserialization-ru-d810a802893e-5fb1a04de4a1758e](../../raw/text-10.0/jsonserialization-ru-d810a802893e-5fb1a04de4a1758e.md); [jsonreader-ru-ff27f8463f3e-86d5566c3325a094](../../raw/text-10.0/jsonreader-ru-ff27f8463f3e-86d5566c3325a094.md); [jsonwriter-ru-9ec154ed880b-41ab3e3bfa574b84](../../raw/text-10.0/jsonwriter-ru-9ec154ed880b-41ab3e3bfa574b84.md); [integration-process-project-element-fe0b29a88e3c-09fad28113ad05b8](../../raw/text-10.0/integration-process-project-element-fe0b29a88e3c-09fad28113ad05b8.md); [integration-process-types-8e189e38bf2c-89f0948750666a1f](../../raw/text-10.0/integration-process-types-8e189e38bf2c-89f0948750666a1f.md); [integration-process-be3cd7b902c7-8ed3f0ae2c2fe9d7](../../raw/text-10.0/integration-process-be3cd7b902c7-8ed3f0ae2c2fe9d7.md); [httprequest-ru-b138f7d5f696-111efe550932e33d](../../raw/text-10.0/httprequest-ru-b138f7d5f696-111efe550932e33d.md); [httpresponse-ru-8fa5b68112a5-a877ad51cd0cc54d](../../raw/text-10.0/httpresponse-ru-8fa5b68112a5-a877ad51cd0cc54d.md); [httpexception-ru-2140341cd0ec-27b4d5469a59de7d](../../raw/text-10.0/httpexception-ru-2140341cd0ec-27b4d5469a59de7d.md); [jsonreaderexception-ru-62be4dbb30ff-c3f2e17aba420a91](../../raw/text-10.0/jsonreaderexception-ru-62be4dbb30ff-c3f2e17aba420a91.md); [webchat-ru-c524a365a12f-bc5c581f2b75f362](../../raw/text-10.0/webchat-ru-c524a365a12f-bc5c581f2b75f362.md); [emailaddress-ru-000c5864525b-308238a5933a1163](../../raw/text-10.0/emailaddress-ru-000c5864525b-308238a5933a1163.md); [dataexchangeonunloadaction-ru-b5eb542d7e2a-c0ae33c6f43be799](../../raw/text-10.0/dataexchangeonunloadaction-ru-b5eb542d7e2a-c0ae33c6f43be799.md); [ftpexception-ru-132dadd916c0-6e2648dc27ee15fa](../../raw/text-10.0/ftpexception-ru-132dadd916c0-6e2648dc27ee15fa.md); [url-ru-3532308ec0d3-7790f5db390661ad](../../raw/text-10.0/url-ru-3532308ec0d3-7790f5db390661ad.md); [httpservice-ru-a5cc07d8bdea-ab24cdd650e47ce8](../../raw/text-10.0/httpservice-ru-a5cc07d8bdea-ab24cdd650e47ce8.md); [integrableapplication-ru-5607393f6b9e-bce256445f999e4b](../../raw/text-10.0/integrableapplication-ru-5607393f6b9e-bce256445f999e4b.md); [integrationschemanodekind-ru-a40f2abdcc09-afbc6397c3e0fc05](../../raw/text-10.0/integrationschemanodekind-ru-a40f2abdcc09-afbc6397c3e0fc05.md); [integrationprocessexecutionoperation-ru-1a618b997df9-7d994d7bed439540](../../raw/text-10.0/integrationprocessexecutionoperation-ru-1a618b997df9-7d994d7bed439540.md); [navigationcommandinfsystems-ru-6a1bc0f8fea0-27145874063dd4b7](../../raw/text-10.0/navigationcommandinfsystems-ru-6a1bc0f8fea0-27145874063dd4b7.md); [jsonignoreproperty-ru-2025b10a49b4-42d7d949c609e8fe](../../raw/text-10.0/jsonignoreproperty-ru-2025b10a49b4-42d7d949c609e8fe.md); [soapservice-ru-fe39d75e5abe-892864cf38273ba9](../../raw/text-10.0/soapservice-ru-fe39d75e5abe-892864cf38273ba9.md); [sftpexception-ru-b1502c5e1bd8-55c50dc44d95ca3b](../../raw/text-10.0/sftpexception-ru-b1502c5e1bd8-55c50dc44d95ca3b.md); [v8administrator-ru-cf51a3199fbf-7ad8f502c961eb7e](../../raw/text-10.0/v8administrator-ru-cf51a3199fbf-7ad8f502c961eb7e.md); [propertylist-ru-2c1ba8924c01-59415fa11e897e82](../../raw/text-10.0/propertylist-ru-2c1ba8924c01-59415fa11e897e82.md); [xmldomnodekind-ru-e99a27009ec2-4b21422abd42c121](../../raw/text-10.0/xmldomnodekind-ru-e99a27009ec2-4b21422abd42c121.md); [xmltransformationexception-ru-6f9c954f3882-b92f1e121cbfb604](../../raw/text-10.0/xmltransformationexception-ru-6f9c954f3882-b92f1e121cbfb604.md); [xmlvalidationexception-ru-52055d7c2301-f3d5c5f6e5c5f67c](../../raw/text-10.0/xmlvalidationexception-ru-52055d7c2301-f3d5c5f6e5c5f67c.md); [xpathexpression-ru-1605402d73a2-043efc6fc8feec97](../../raw/text-10.0/xpathexpression-ru-1605402d73a2-043efc6fc8feec97.md); [enums-1371c92b66bf-281049a35da02ffd](../../raw/text-10.0/enums-1371c92b66bf-281049a35da02ffd.md); [autooffsetreset-ru-1776ea84afc4-ff77aef3419c7995](../../raw/text-10.0/autooffsetreset-ru-1776ea84afc4-ff77aef3419c7995.md); [integrableapplicationname-ru-dded7fda26a0-3418bbf24f173715](../../raw/text-10.0/integrableapplicationname-ru-dded7fda26a0-3418bbf24f173715.md); [ftp-0f2eb1c44972-b88f73c43a80d5e0](../../raw/text-10.0/ftp-0f2eb1c44972-b88f73c43a80d5e0.md); [ftpsource-ru-a43e85e4ee35-d51a46380b7991bd](../../raw/text-10.0/ftpsource-ru-a43e85e4ee35-d51a46380b7991bd.md); [amqp-protocol-13ae4cada8e6-3cb0f0d130e23475](../../raw/text-10.0/amqp-protocol-13ae4cada8e6-3cb0f0d130e23475.md); [httpservice-77f3ea4c73b2-8d8948ca03d89d1d](../../raw/text-10.0/httpservice-77f3ea4c73b2-8d8948ca03d89d1d.md)
> Updated: 2026-10-05

Версия: `10.0`.

## Тематические объяснения

- [HTTP-клиент и обработка JSON](http-and-json.md) — Как связать HTTP-взаимодействие с документированными средствами JSON.
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md) — Схема процесса и явное ограничение доступности в облачной версии.
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md) — Серверный запрос, актуальные имена ответа, чтение JSON и разные виды ошибок.

## Оглавление справочника

Счётчики рассчитаны по реестру покрытия. Точные источники каждого описания находятся в соответствующем групповом индексе.

| Группа | Статей |
| --- | ---: |
| [Руководство разработчика](index-guide-01.md) | 81 |
| [XBSL: Std::CollaborationSystem](index-xbsl-collaborationsystem-01.md) | 30 |
| [XBSL: Std::Email](index-xbsl-email-01.md) | 29 |
| [XBSL: Std::ExchangePlans](index-xbsl-exchangeplans-01.md) | 12 |
| [XBSL: Std::Ftp](index-xbsl-ftp-01.md) | 3 |
| [XBSL: Std::Http](index-xbsl-http-01.md) | 12 |
| [XBSL: Std::HttpServices](index-xbsl-httpservices-01.md) | 5 |
| [XBSL: Std::IntegrableApplications](index-xbsl-integrableapplications-01.md) | 6 |
| [XBSL: Std::IntegrationBus](index-xbsl-integrationbus-01.md) | 30 |
| [XBSL: Std::IntegrationBus::Events](index-xbsl-integrationbus-events-01.md) | 13 |
| [XBSL: Std::IntegrationBus::Interface](index-xbsl-integrationbus-interface-01.md) | 4 |
| [XBSL: Std::Json](index-xbsl-json-01.md) | 17 |
| [XBSL: Std::SoapServices](index-xbsl-soapservices-01.md) | 10 |
| [XBSL: Std::Ssh](index-xbsl-ssh-01.md) | 9 |
| [XBSL: Std::V8::Administration](index-xbsl-v8-administration-01.md) | 16 |
| [XBSL: Std::Xml](index-xbsl-xml-01.md) | 9 |
| [XBSL: Std::Xml::Dom](index-xbsl-xml-dom-01.md) | 3 |
| [XBSL: Std::Xml::Transformation](index-xbsl-xml-transformation-01.md) | 3 |
| [XBSL: Std::Xml::Validation](index-xbsl-xml-validation-01.md) | 3 |
| [XBSL: Std::Xml::XPath](index-xbsl-xml-xpath-01.md) | 4 |
| [Каталоги справочников](index-catalogs-01.md) | 3 |
| [Перечисления схем интеграции](index-schema-enums-01.md) | 11 |
| [Прикладные и генерируемые типы XBSL](index-generated-01.md) | 54 |
| [Пространства имён XBSL](index-namespaces-01.md) | 19 |
| [Схемы процессов интеграции](index-schemas-01.md) | 36 |
| [Термины](index-glossary-01.md) | 6 |
| [Элементы проекта](index-elements-01.md) | 33 |

## See Also

- [Общий индекс](../index.md)
- [Пространства имён](../stdlib/namespaces.md)
- [Компоненты: руководство и контракты](../interface/component-map.md)
- [Элементы проекта и порождаемые типы](../project/element-map.md)
