# Схема процесса интеграции

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationprocessschema-7afd29ed6120-17a8f41bbee6d1c7](../../raw/text-10.0/integrationprocessschema-7afd29ed6120-17a8f41bbee6d1c7.md); [ae870e9008d703960e972b1ded28630f913a765619b9ab04ef22de7631f5316f-077739211bc4969a](../../raw/figures/ae870e9008d703960e972b1ded28630f913a765619b9ab04ef22de7631f5316f-077739211bc4969a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Каталог справочника.

Владелец: IntegrationProcessSchema.

Имена для поиска: `Схема процесса интеграции`, `IntegrationProcessSchema`.

## Обзор

Справочник по элементам схемы [процесса интеграции](integration-process-project-element-fe0b29a88e3c.md).

## Документированный контракт и примеры

Справочник по элементам схемы [процесса интеграции](integration-process-project-element-fe0b29a88e3c.md).

## Процесс интеграции

Элемент проекта вида **Процесс интеграции** используется для описания взаимодействия «1С:Предприятие.Элемента» с информационными системами. **Схема** — основная часть процесса интеграции, которая состоит из узлов и связей. Она наглядно показывает движение сообщений от информационных систем-источников к информационным системам-получателям сообщений.

Схема процесса интеграции [Описание иллюстрации](../../raw/figures/ae870e9008d703960e972b1ded28630f913a765619b9ab04ef22de7631f5316f-077739211bc4969a.md)

## Узлы

### Источники

[FtpИсточник](ftpsource-ru-a43e85e4ee35.md)

[JmsИсточник](jmssource-ru-5b677d0081a9.md)

[KafkaИсточник](kafkasource-ru-c56e6ff7a433.md)

[RabbitMqИсточник](rabbitmqsource-ru-04b97d31ad6b.md)

[Канал1СИсточник](channel1csource-ru-ac34f562fcf8.md)

[ОчередьШиныИсточник](esbqueuesource-ru-b5a2104cfe01.md)

[ПрограммныйИсточник](programmaticsource-ru-72d424dfebce.md)

[Таймер](timer-ru-76de20ebcf27.md)

[ФайлИсточник](filesource-ru-5279f8af1efd.md)

### Приемники

[FtpНазначение](ftpdestination-ru-fd6e5b762afe.md)

[JmsНазначение](jmsdestination-ru-886444a7d2df.md)

[KafkaНазначение](kafkadestination-ru-0a2daa6ce1ff.md)

[RabbitMqНазначение](rabbitmqdestination-ru-2854b502788c.md)

[Канал1СНазначение](channel1cdestination-ru-5a181f76630a.md)

[ОчередьШиныНазначение](esbqueuedestination-ru-e38871405326.md)

[ФайлНазначение](filedestination-ru-be5b795b27a8.md)

### Маршрутизаторы

[МаршрутизаторПоСодержимому](contentbasedrouter-ru-9eb143181111.md)

### Другие

[Http](http-ru-ca84287d0684.md)

[Sql](sql-ru-907f0cb12bde.md)

[ГруппаУчастников](participantsgroup-ru-01bdfe928fa9.md)

[Транслятор](translator-ru-e20309abf2b2.md)

[Разделитель](splitter-ru-3afc04263c71.md)

[Маршрут](schemaroute-89110a4fd23d.md)

[Связь](schemagrouplink-ru-b3a8d300ba44.md)

## See Also

- [Навигатор раздела](overview.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [Схема процесса интеграции](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/).
