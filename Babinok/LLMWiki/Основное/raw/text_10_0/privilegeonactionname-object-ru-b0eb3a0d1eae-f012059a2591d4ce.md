# {ИмяПраваНаДействие}.Объект

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/PrivilegeOnActionName.Object_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/PrivilegeOnActionName.Object_ru/index.html
> SHA256: 7f7452355261c0e9d2c35e074e19f6ed4f989d4809d5f0af90075a53b83feefe
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПраваНаДействие}.Объект` `Доступность: Сервер`

Пользовательское право на действие

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ПравоДоступа](../../wiki/security/accessprivilege-ru-ec1f634a9bdc.md), [ПравоНаДействие.Объект](../../wiki/stdlib/privilegeonaction-object-ru-1518561ced61.md)

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

Переопределение: [Хеш](../../wiki/stdlib/privilegeonactionname-object-ru-b0eb3a0d1eae.md)

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление права на действие.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/stdlib/privilegeonactionname-object-ru-b0eb3a0d1eae.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ПравоНаДействие.Объект

[Пересчитать](../../wiki/stdlib/privilegeonaction-object-ru-1518561ced61.md)
