# СохранятьСообщениеНаСторонеБрокера

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [savemessageonbrokerside-ru-4cd70d9c6628-2b9a31e5c2bb0b92](../../raw/text-10.0/savemessageonbrokerside-ru-4cd70d9c6628-2b9a31e5c2bb0b92.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Перечисление схемы интеграции.

Владелец: IntegrationProcessSchema.

Имена для поиска: `СохранятьСообщениеНаСторонеБрокера`, `SaveMessageOnBrokerSide`, `Std::Enums::SaveMessageOnBrokerSide`.

## Обзор

Позволяет настроить сохранение сообщений на стороне брокера RabbitMQ.

## Документированный контракт и примеры

Позволяет настроить сохранение сообщений на стороне брокера RabbitMQ.

---

## Литералы

#### НеСохранятьСообщение

Отправленные из «1С:Предприятие.Элемента» сообщения не сохраняются в брокере RabbitMQ. Отправляются «временные» (transient) сообщения, со свойством RabbitMQ-сообщения `DeliveryMode=1`.

---

#### СохранятьСообщение

Отправленные из «1С:Предприятие.Элемента» сообщения сохраняются в брокере RabbitMQ. Отправляются «постоянные» (persistent) сообщения, со свойством RabbitMQ-сообщения `DeliveryMode=2`.

Чтобы сообщения сохранялись в RabbitMQ, помимо установки соответствующего значения свойства узла [RabbitMqНазначение](rabbitmqdestination-ru-2854b502788c.md) **СохранятьСообщениеНаСторонеБрокера**, также необходимо на стороне самого брокера:

- для обмена (Exchange) установить свойство
  
  `Durable=True`
  
  ;
- для очереди (Queue) установить свойство
  
  `Durable=True`
  
  .

---

#### ИзОбработчика

Обработчик определяет, следует ли сохранять сообщение на стороне RabbitMq. Имя обработчика указывается в свойстве [ВыборСохраненияСообщенияНаСторонеБрокера](rabbitmqdestination-ru-2854b502788c.md).

---

## See Also

- [Навигатор раздела](overview.md)
- [Перечисления — Каталог справочника: IntegrationProcessSchema](enums-1371c92b66bf.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [СохранятьСообщениеНаСторонеБрокера](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/Std/Enums/SaveMessageOnBrokerSide_ru/).
