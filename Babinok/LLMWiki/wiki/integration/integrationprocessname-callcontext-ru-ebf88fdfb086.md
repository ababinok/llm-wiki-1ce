# {ИмяПроцессаИнтеграции}.КонтекстВызова

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationprocessname-callcontext-ru-ebf88fdfb086-c90f1b2f346cde97](../../raw/text-10.0/integrationprocessname-callcontext-ru-ebf88fdfb086-c90f1b2f346cde97.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: IntegrationProcessName.

Имена для поиска: `{ИмяПроцессаИнтеграции}.КонтекстВызова`, `IntegrationProcessName.CallContext`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.КонтекстВызова`, `DeveloperName::ProjectName::SubsystemName::IntegrationProcessName.CallContext`.

## Обзор

*Базовые типы:* [КонтекстВызоваИнтеграции](integrationcallcontext-ru-439a69684b27.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.КонтекстВызова` `Доступность: Сервер`

Контекст вызова обработчика.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [КонтекстВызоваИнтеграции](integrationcallcontext-ru-439a69684b27.md), [Объект](../stdlib/object-ru-9e351f286699.md)

---

## Свойства

### Участник

`Версия 8.0 и выше`

`Доступность: Сервер` `ТолькоЧтение`

```
Участник: ИмяИнформационныхСистем.Данные?
```

Данные участника интеграции, для которого вызван обработчик, или `Неопределено`, если узел не связан с группой участников.

---

### Участник

`Версия 7.0 и ниже`

> **Исторический контракт:** верхняя граница версии 7.0; не используйте этот член для 10.0.


`Доступность: Сервер` `ТолькоЧтение`

```
Участник: ИнформационныеСистемы.Данные?
```

Свойство заменено на [Участник](integrationprocessname-callcontext-ru-ebf88fdfb086.md).

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### КонтекстВызоваИнтеграции

[ТекущийМаршрут](integrationcallcontext-ru-439a69684b27.md), [ТекущийУзел](integrationcallcontext-ru-439a69684b27.md)

## See Also

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](../stdlib/subsystemname-59b031c3e78f.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяПроцессаИнтеграции}.КонтекстВызова](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.CallContext_ru/).
