# {ИмяВычисляемогоКлючаДоступа}.Объект

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ComputableAccessKeyName.Object_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/ComputableAccessKeyName.Object_ru/index.html
> SHA256: f73b7472c5ef1c3f1a7fde37ecb34f8d1b0b3972bed82c885cb47ada36d75f7c
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 10.0 и выше`

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяВычисляемогоКлючаДоступа}.Объект` `Доступность: Сервер`

Пользовательский вычисляемый ключ доступа.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ВычисляемыйКлючДоступа.Объект](../../wiki/security/computableaccesskey-object-ru-0d0b5f774cb0.md), [КлючДоступа.Объект](../../wiki/security/accesskey-object-ru-4c5322ab4636.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### {ИмяВычисляемогоКлючаДоступа}.Объект

`Доступность: Сервер`

```
{ИмяВычисляемогоКлючаДоступа}.Объект(
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

Переопределение: [Хеш](../../wiki/security/computableaccesskeyname-object-ru-513b36fec08b.md)

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

### ВычисляемыйКлючДоступа.Объект

[Пересчитать](../../wiki/security/computableaccesskey-object-ru-0d0b5f774cb0.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/security/computableaccesskeyname-object-ru-513b36fec08b.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных событий

### КлючДоступа.Объект

[Хеш](../../wiki/security/accesskey-object-ru-4c5322ab4636.md)
