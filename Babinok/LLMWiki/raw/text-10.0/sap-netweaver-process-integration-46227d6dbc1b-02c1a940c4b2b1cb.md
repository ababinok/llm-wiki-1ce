# Взаимодействие с SAP NetWeaver Process Integration (SAP PI)

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/sap-netweaver-process-integration/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/sap-netweaver-process-integration/index.html
> SHA256: 78665a1851ef68242ca40d7fc73bb00977c085346eb6da34490742efd4b6f366
> SnapshotCreated: 2026-10-05
> Rendition: verified text

В «1С:Предприятие.Элементу» для взаимодействия с приложением SAP NetWeaver Process Integration предназначены узлы процесса интеграции вида [ОчередьШиныИсточник](../../wiki/integration/esb-queue-source-b4517ca0b7f6.md) и [ОчередьШиныНазначение](../../wiki/integration/esb-queue-destination-983a8f6d448b.md). Эти узлы позволяют настроить асинхронную интеграцию с SAP PI по протоколу JMS. Внешняя информационная система может подключиться к очередям данного вида и отправлять сообщения в эти очереди либо забирать сообщения из них.

> [!TIP] совет
> Для подключения к очередям «1С:Предприятие.Элемента» в SAP PI рекомендуется использовать библиотеку JMS-клиента **artemis-jms-client-all-2.37.jar**. В SAP PI данный клиент следует устанавливать через провайдер внешних библиотек для адаптера JMS.


Совет. [Описание иллюстрации](../figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md)
