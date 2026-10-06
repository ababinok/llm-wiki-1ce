# Взаимодействие с SAP NetWeaver Process Integration (SAP PI)

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [sap-netweaver-process-integration-46227d6dbc1b-02c1a940c4b2b1cb](../../raw/text-10.0/sap-netweaver-process-integration-46227d6dbc1b-02c1a940c4b2b1cb.md); [ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1](../../raw/figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Взаимодействие с SAP NetWeaver Process Integration (SAP PI)`, `sap-netweaver-process-integration`.

## Обзор

В «1С:Предприятие.Элементу» для взаимодействия с приложением SAP NetWeaver Process Integration предназначены узлы процесса интеграции вида [ОчередьШиныИсточник](esb-queue-source-b4517ca0b7f6.md) и [ОчередьШиныНазначение](esb-queue-destination-983a8f6d448b.md).

## Документированный контракт и примеры

В «1С:Предприятие.Элементу» для взаимодействия с приложением SAP NetWeaver Process Integration предназначены узлы процесса интеграции вида [ОчередьШиныИсточник](esb-queue-source-b4517ca0b7f6.md) и [ОчередьШиныНазначение](esb-queue-destination-983a8f6d448b.md). Эти узлы позволяют настроить асинхронную интеграцию с SAP PI по протоколу JMS. Внешняя информационная система может подключиться к очередям данного вида и отправлять сообщения в эти очереди либо забирать сообщения из них.

> [!TIP] совет
> Для подключения к очередям «1С:Предприятие.Элемента» в SAP PI рекомендуется использовать библиотеку JMS-клиента **artemis-jms-client-all-2.37.jar**. В SAP PI данный клиент следует устанавливать через провайдер внешних библиотек для адаптера JMS.


Совет. [Описание иллюстрации](../../raw/figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md)

## See Also

- [Навигатор раздела](overview.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [Взаимодействие с SAP NetWeaver Process Integration (SAP PI)](https://1cmycloud.com/console/help/element/10.0/docs/topics/sap-netweaver-process-integration/).
