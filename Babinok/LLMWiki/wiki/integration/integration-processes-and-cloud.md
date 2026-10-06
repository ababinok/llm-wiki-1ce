# Процессы интеграции и ограничения облака

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integration-process-project-element-fe0b29a88e3c-09fad28113ad05b8](../../raw/text-10.0/integration-process-project-element-fe0b29a88e3c-09fad28113ad05b8.md); [ae870e9008d703960e972b1ded28630f913a765619b9ab04ef22de7631f5316f-077739211bc4969a](../../raw/figures/ae870e9008d703960e972b1ded28630f913a765619b9ab04ef22de7631f5316f-077739211bc4969a.md); [71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d](../../raw/figures/71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d.md); [508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md); [integration-process-types-8e189e38bf2c-89f0948750666a1f](../../raw/text-10.0/integration-process-types-8e189e38bf2c-89f0948750666a1f.md); [4cccb773b9768524985359140dd3416af620382dd4a4ba8010b8769025bd2492-130271c1e423e97c](../../raw/figures/4cccb773b9768524985359140dd3416af620382dd4a4ba8010b8769025bd2492-130271c1e423e97c.md); [integration-process-be3cd7b902c7-8ed3f0ae2c2fe9d7](../../raw/text-10.0/integration-process-be3cd7b902c7-8ed3f0ae2c2fe9d7.md); [a9e91b529854f270aff0224dea9a1d28ceec67ff9f85d11f2413a87cca0d0afe-c449cf7d22b470d4](../../raw/figures/a9e91b529854f270aff0224dea9a1d28ceec67ff9f85d11f2413a87cca0d0afe-c449cf7d22b470d4.md); [988b8e43ddbce6fa4ca374839a411ae3988aa06f0c8c4a5113332183a347952f-6f3e3663b922cadc](../../raw/figures/988b8e43ddbce6fa4ca374839a411ae3988aa06f0c8c4a5113332183a347952f-6f3e3663b922cadc.md); [aa4b070c5713d7dbfcab30b45b4ad170f4ead4785e36806b3fae05acdd944b65-3664f3e2d659a41d](../../raw/figures/aa4b070c5713d7dbfcab30b45b4ad170f4ead4785e36806b3fae05acdd944b65-3664f3e2d659a41d.md); [414e17811b8cf896be99af87b5ca227ffba33e43f25fa5f441bc95f091246328-a47c8957baeeceab](../../raw/figures/414e17811b8cf896be99af87b5ca227ffba33e43f25fa5f441bc95f091246328-a47c8957baeeceab.md); [d4c7c2097288898230509bf5779dd215ec82f7a085d4621ab72bbb4adda4c588-2bd0ca601b4cbe73](../../raw/figures/d4c7c2097288898230509bf5779dd215ec82f7a085d4621ab72bbb4adda4c588-2bd0ca601b4cbe73.md); [69dac880acb06e412e01279bd4f648645dd1bbd1e417423af1ba3551b52a5ebb-2f624ab3b02747a2](../../raw/figures/69dac880acb06e412e01279bd4f648645dd1bbd1e417423af1ba3551b52a5ebb-2f624ab3b02747a2.md); [67ae80fa275cfbf0b3960fe1acb69ed5a24ec03f2daf69bdd6a303e73b7a8a16-ea54e6a00efe5b31](../../raw/figures/67ae80fa275cfbf0b3960fe1acb69ed5a24ec03f2daf69bdd6a303e73b7a8a16-ea54e6a00efe5b31.md); [d55c8be8069b3addf419865d583f8ba4235b775efa01d94f875395c455e1d32f-8128e6ac4a603e75](../../raw/figures/d55c8be8069b3addf419865d583f8ba4235b775efa01d94f875395c455e1d32f-8128e6ac4a603e75.md); [be9404ececa060cdc3c80d723c4c387b0e9707e6b1167c849e45098178b6ab11-0a8d868f07d26453](../../raw/figures/be9404ececa060cdc3c80d723c4c387b0e9707e6b1167c849e45098178b6ab11-0a8d868f07d26453.md); [3a131deb56ab4c78716f2e26fc8229ee513dd2a4e0e3010ab277f43c9156e94b-a1952d7b86088a1d](../../raw/figures/3a131deb56ab4c78716f2e26fc8229ee513dd2a4e0e3010ab277f43c9156e94b-a1952d7b86088a1d.md); [47d55008a85a3fab930b811a85c93110c1e6306bb59fb155822a107599f5887d-2165ba9d8a40ca23](../../raw/figures/47d55008a85a3fab930b811a85c93110c1e6306bb59fb155822a107599f5887d-2165ba9d8a40ca23.md)
> Updated: 2026-10-05

Версия: `10.0`.

## Обзор

Процесс интеграции описывает взаимодействие с внешними информационными системами. Его схема состоит из узлов, маршрутов, групп участников и связей и показывает движение сообщений.

## Доступность

В документации прямо указано: элемент проекта «Процесс интеграции» недоступен в облачной версии «1С:Предприятие.Элемента». Наличие его описания в этой базе не означает доступность в целевом облачном проекте.

## Схема и программный контракт

Узлы обозначают действия с сообщением, маршруты — движение внутри Элемента, связи — обмен с внешними системами. Свойства схемы и порождаемые программные типы описаны отдельно и должны проверяться совместно.

Если задача выполняется в облаке, сначала определите доступный механизм интеграции по документации. Не предлагайте создать процесс интеграции, игнорируя указанное ограничение.

## Документация и примеры

- [Элемент проекта вида «Процесс интеграции» — Руководство](integration-process-project-element-fe0b29a88e3c.md)
- [Типы, порождаемые элементом проекта вида «Процесс интеграции» — Руководство](integration-process-types-8e189e38bf2c.md)
- [Создание и редактирование элемента «Процесс интеграции» — Руководство](integration-process-be3cd7b902c7.md)

## See Also

- [Навигатор раздела](overview.md)
- [http-and-json](http-and-json.md)
- [application-architecture](../project/application-architecture.md)
