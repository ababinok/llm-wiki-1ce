# {ИмяВыдаваемогоКлючаДоступа}.Объект

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/GrantableAccessKeyName.Object_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/GrantableAccessKeyName.Object_ru/index.html
> SHA256: f6644a1d30797e38aa21f81bef16c321c0274e2d47ed0dec4a0f6cbc2ab8081f
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяВыдаваемогоКлючаДоступа}.Объект` `Доступность: Сервер`

Пользовательский выдаваемый ключ доступа.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ВыдаваемыйКлючДоступа.Объект](../../wiki/security/grantableaccesskey-object-ru-851edad3d627.md), [КлючДоступа.Объект](../../wiki/security/accesskey-object-ru-4c5322ab4636.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяВыдаваемогоКлючаДоступа}.Объект

`Доступность: Сервер`

```
{ИмяВыдаваемогоКлючаДоступа}.Объект(
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

Хеш ключа.

Переопределение: [Хеш](../../wiki/security/grantableaccesskeyname-object-ru-cc8812305674.md)

---

### {ИмяПараметра}

`Доступность: Сервер`

```
ИмяПараметра: ТипПараметра
```

Параметр ключа доступа.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление ключа доступа.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### ВыдаваемыйКлючДоступа.Объект

[Выдать](../../wiki/security/grantableaccesskey-object-ru-851edad3d627.md)

[Отозвать](../../wiki/security/grantableaccesskey-object-ru-851edad3d627.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/security/grantableaccesskeyname-object-ru-cc8812305674.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных событий

### КлючДоступа.Объект

[Хеш](../../wiki/security/accesskey-object-ru-4c5322ab4636.md)
