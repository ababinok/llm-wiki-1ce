# ОписаниеПараметраВнешнейСистемыВзаимодействия

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [externalcollaborationsystemparameterdescription-ru-80c4d8287922-401788349ac9173a](../../raw/text-10.0/externalcollaborationsystemparameterdescription-ru-80c4d8287922-401788349ac9173a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / CollaborationSystem.

Имена для поиска: `ОписаниеПараметраВнешнейСистемыВзаимодействия`, `ExternalCollaborationSystemParameterDescription`, `Стд::СистемаВзаимодействия::ОписаниеПараметраВнешнейСистемыВзаимодействия`, `Std::CollaborationSystem::ExternalCollaborationSystemParameterDescription`.

## Обзор

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Стд::СистемаВзаимодействия::ОписаниеПараметраВнешнейСистемыВзаимодействия` `Доступность: Сервер`

Описание параметра внешней системы

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Свойства

### Имя

`Доступность: Сервер` `ТолькоЧтение`

```
Имя: Строка
```

Имя параметра

---

### Обязательный

`Доступность: Сервер` `ТолькоЧтение`

```
Обязательный: Булево
```

Признак того, что параметр является обязательным параметром.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление описания параметра внешней системы.

**Переопределение** [Объект::ВСтроку](../stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md) [(Переопределение)](externalcollaborationsystemparameterdescription-ru-80c4d8287922.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::СистемаВзаимодействия — Пространство имён XBSL: Std](collaborationsystem-a87edf727e1d.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ОписаниеПараметраВнешнейСистемыВзаимодействия](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/CollaborationSystem/ExternalCollaborationSystemParameterDescription_ru/).
