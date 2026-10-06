# {ИмяПраваНаДействие}.Объект

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [privilegeonactionname-object-ru-b0eb3a0d1eae-f012059a2591d4ce](../../raw/text-10.0/privilegeonactionname-object-ru-b0eb3a0d1eae-f012059a2591d4ce.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Порождаемый тип XBSL.

Владелец: PrivilegeOnActionName.

Имена для поиска: `{ИмяПраваНаДействие}.Объект`, `PrivilegeOnActionName.Object`, `{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПраваНаДействие}.Объект`, `DeveloperName::ProjectName::SubsystemName::PrivilegeOnActionName.Object`.

## Обзор

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ПравоДоступа](../security/accessprivilege-ru-ec1f634a9bdc.md), [ПравоНаДействие.Объект](privilegeonaction-object-ru-1518561ced61.md)

## Документированный контракт и примеры

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПраваНаДействие}.Объект` `Доступность: Сервер`

Пользовательское право на действие

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [ПравоДоступа](../security/accessprivilege-ru-ec1f634a9bdc.md), [ПравоНаДействие.Объект](privilegeonaction-object-ru-1518561ced61.md)

---

## Конструкторы

### {ИмяПраваНаДействие}.Объект

`Доступность: Сервер`

```
{ИмяПраваНаДействие}.Объект(
  <ИмяПараметра1>: <ТипПараметра1> = <ЗначениеПоУмолчаниюПараметра1>,
  ....<ИмяПараметраN>: <ТипПараметраN> = <ЗначениеПоУмолчаниюПараметраN>)
```

Конструктор по параметрам.

---

## Свойства

### Хеш

`Доступность: Сервер` `ТолькоЧтение`

```
Хеш: Байты
```

Хеш права на действие.

Переопределение: [Хеш](privilegeonactionname-object-ru-b0eb3a0d1eae.md)

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление права на действие.

**Переопределение** [Объект::ВСтроку](object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](object-ru-9e351f286699.md) [(Переопределение)](privilegeonactionname-object-ru-b0eb3a0d1eae.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

### ПравоНаДействие.Объект

[Пересчитать](privilegeonaction-object-ru-1518561ced61.md)

## See Also

- [Навигатор раздела](../project/overview.md)
- [{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы} — Пространство имён XBSL: DeveloperName / ProjectName](subsystemname-59b031c3e78f.md)
- [Как устроено приложение Элемента](../project/application-architecture.md)

Оригинал: [{ИмяПраваНаДействие}.Объект](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/PrivilegeOnActionName.Object_ru/).
