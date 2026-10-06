# AMQP-протокол

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/terms/amqp-protocol/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/terms/amqp-protocol/index.html
> SHA256: 534f3ff345613d712fef6b1cebc846d5e8990c7151d03a919204c64bacb5fe4a
> SnapshotCreated: 2026-10-05
> Rendition: verified text

AMQP (Advanced Message Queuing Protocol) — это открытый стандартный протокол прикладного уровня, предназначенный для асинхронного обмена сообщениями между компонентами распределенных систем.

В «1С:Предприятие.Элементе» протокол AMQP используется для подключения внешних информационных систем.

В AMQP сообщения передаются через брокер. Интеграция между информационными базами «1С:Предприятия» происходит через узлы [процесса интеграции](../../wiki/integration/integration-process-be3cd7b902c7.md) [Канал1СИсточник](../../wiki/integration/channel-1c-source-ddb853b7d45d.md) и [Канал1СНазначение](../../wiki/integration/channel-1c-destination-3c02e5ef031f.md) по протоколу AMQP с использованием брокера интеграционной шины. Внешняя система подключается к очередям, через которые отправляются и забираются сообщения.

## См. также

- [Отправка и получение сообщений по протоколу AMQP из стороннего приложения](../../wiki/integration/esb-demo-example-5-cef280458c37.md)
- [Настройка обмена сообщениями между базой на платформе «1С:Предприятие» и брокером сообщений RabbitMQ](../../wiki/integration/esb-demo-example-2-32b327ad70c7.md)
- Узлы схемы процесса интеграции
  
  [RabbitMqИсточник](../../wiki/integration/rabbitmq-source-a0583a4c910a.md)
  
  и
  
  [RabbitMqНазначение](../../wiki/project/delivered-messages-d48678a57c96.md)
