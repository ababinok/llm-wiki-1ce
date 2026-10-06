# СохранятьСообщениеНаСторонеБрокера

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/Std/Enums/SaveMessageOnBrokerSide_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/IntegrationProcessSchema/Std/Enums/SaveMessageOnBrokerSide_ru/index.html
> SHA256: 9f76052b82b6dc612a3c02dc48536657347c64f929f82f3afe9f50d2f6c47951
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Позволяет настроить сохранение сообщений на стороне брокера RabbitMQ.

---

## Литералы

#### НеСохранятьСообщение

Отправленные из «1С:Предприятие.Элемента» сообщения не сохраняются в брокере RabbitMQ. Отправляются «временные» (transient) сообщения, со свойством RabbitMQ-сообщения `DeliveryMode=1`.

---

#### СохранятьСообщение

Отправленные из «1С:Предприятие.Элемента» сообщения сохраняются в брокере RabbitMQ. Отправляются «постоянные» (persistent) сообщения, со свойством RabbitMQ-сообщения `DeliveryMode=2`.

Чтобы сообщения сохранялись в RabbitMQ, помимо установки соответствующего значения свойства узла [RabbitMqНазначение](../../wiki/integration/rabbitmqdestination-ru-2854b502788c.md) **СохранятьСообщениеНаСторонеБрокера**, также необходимо на стороне самого брокера:

- для обмена (Exchange) установить свойство
  
  `Durable=True`
  
  ;
- для очереди (Queue) установить свойство
  
  `Durable=True`
  
  .

---

#### ИзОбработчика

Обработчик определяет, следует ли сохранять сообщение на стороне RabbitMq. Имя обработчика указывается в свойстве [ВыборСохраненияСообщенияНаСторонеБрокера](../../wiki/integration/rabbitmqdestination-ru-2854b502788c.md).

---
