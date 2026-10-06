# HTTP-клиент и обработка JSON

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [http-requests-2fbe5c3df089-9ac02208b677c265](../../raw/text-10.0/http-requests-2fbe5c3df089-9ac02208b677c265.md); [069ae326eb32ca3c1e6bcc43cb220f35e90aa51a0d7ea93f4901e612b11479ab-4d3c45ed10bf9b60](../../raw/figures/069ae326eb32ca3c1e6bcc43cb220f35e90aa51a0d7ea93f4901e612b11479ab-4d3c45ed10bf9b60.md); [httpclient-ru-fc35d11b0b5c-225568ec91e9d235](../../raw/text-10.0/httpclient-ru-fc35d11b0b5c-225568ec91e9d235.md); [work-with-json-7cef407607e5-9dfff58948d1d868](../../raw/text-10.0/work-with-json-7cef407607e5-9dfff58948d1d868.md); [508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md); [jsonserialization-ru-d810a802893e-5fb1a04de4a1758e](../../raw/text-10.0/jsonserialization-ru-d810a802893e-5fb1a04de4a1758e.md); [jsonreader-ru-ff27f8463f3e-86d5566c3325a094](../../raw/text-10.0/jsonreader-ru-ff27f8463f3e-86d5566c3325a094.md); [jsonwriter-ru-9ec154ed880b-41ab3e3bfa574b84](../../raw/text-10.0/jsonwriter-ru-9ec154ed880b-41ab3e3bfa574b84.md)
> Updated: 2026-10-05

Версия: `10.0`.

## Обзор

HTTP-запрос и обработка JSON решают разные части интеграции. Сначала сверяйте контракт `КлиентHttp` и полученного ответа, затем выбирайте механизм чтения или записи JSON. Точные конструкторы, методы, типы потоков и окружения находятся в справочных статьях.

## Выбор режима JSON

`СериализацияJson` используется для объектного чтения и записи. `ЧтениеJson` и `ЗаписьJson` предоставляют потоковую работу. Документация также описывает смешанный режим: потоковая навигация до нужного объекта и объектная обработка этого фрагмента.

Объектная работа загружает документ целиком. Потоковый режим обрабатывает его по частям и применяется для больших документов или сложной вложенности. При выборе режима учитывайте ограничения облака, приведённые в статье «Работа с JSON».

## Проверка интеграционного кода

Не подставляйте сигнатуры HTTP-клиента или сериализатора из других языков. Проверьте точный тип источника и приёмника, настройки сериализации, возможные исключения и доступность операций в нужном окружении. Примеры чтения и записи сохранены рядом с контрактами.

## Документация и примеры

- [HTTP-запросы — Руководство](http-requests-2fbe5c3df089.md)
- [КлиентHttp — Программный тип XBSL: Std / Http](httpclient-ru-fc35d11b0b5c.md)
- [Работа с JSON — Руководство](work-with-json-7cef407607e5.md)
- [СериализацияJson — Программный тип XBSL: Std / Json](jsonserialization-ru-d810a802893e.md)
- [ЧтениеJson — Программный тип XBSL: Std / Json](jsonreader-ru-ff27f8463f3e.md)
- [ЗаписьJson — Программный тип XBSL: Std / Json](jsonwriter-ru-9ec154ed880b.md)

## See Also

- [Навигатор раздела](overview.md)
- [integration-processes-and-cloud](integration-processes-and-cloud.md)
- [client-server-execution](../language/client-server-execution.md)
- [access-keys-and-permissions](../security/access-keys-and-permissions.md)
