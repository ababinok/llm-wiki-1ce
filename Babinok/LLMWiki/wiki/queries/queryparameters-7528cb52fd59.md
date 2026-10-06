# ПараметрыЗапроса

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [queryparameters-7528cb52fd59-78cba19eede0efb8](../../raw/text-10.0/queryparameters-7528cb52fd59-78cba19eede0efb8.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Свойство элемента проекта.

Владелец: Отчет.

Имена для поиска: `ПараметрыЗапроса`, `QueryParameters`, `Std::ProjectElements::Report::QueryParameters`.

## Обзор

Параметры запроса.

## Документированный контракт и примеры

#### ПараметрыЗапроса

```yaml
ПараметрыЗапроса: ПараметрОтчета[]
```

Параметры запроса. Свойство может быть пустым, если [запрос](use-query-to-create-report-3cf7e26dbbbc.md), выступающий в качестве источника данных для отчета, не содержит параметров.

В свойстве должны быть указаны все параметры, используемые в запросе. Недопустимо указывать параметры, которые отсутствуют в тексте запроса.

## See Also

- [Навигатор раздела](../project/overview.md)
- [Отчет — Элемент проекта](../project/report-76b54cc6c05b.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [ПараметрыЗапроса](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/Report/QueryParameters/).
