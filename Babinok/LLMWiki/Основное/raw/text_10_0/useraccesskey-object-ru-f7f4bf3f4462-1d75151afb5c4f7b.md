# КлючДоступаПользователя.Объект

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccessControl/UserAccessKey.Object_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccessControl/UserAccessKey.Object_ru/index.html
> SHA256: ebe9c8974a44f6c5363adaf8cda4079824aa387c4426943de0a817eead09cf08
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::КонтрольДоступа::КлючДоступаПользователя.Объект` `Доступность: Сервер`

Ключ доступа конкретного пользователя.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ВычисляемыйКлючДоступа.Объект](../../wiki/security/computableaccesskey-object-ru-0d0b5f774cb0.md), [КлючДоступа.Объект](../../wiki/security/accesskey-object-ru-4c5322ab4636.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### КлючДоступаПользователя.Объект

`Доступность: Сервер`

```
КлючДоступаПользователя.Объект(Владелец: Пользователи.Ссылка?)
```

Создает ключ доступа указанного пользователя

`Владелец`

.

---

## Свойства

### Владелец

`Доступность: Сервер`

```
Владелец: Пользователи.Ссылка?
```

Ссылка на пользователя-владельца ключа доступа.

---

### Хеш

`Доступность: Сервер` `ТолькоЧтение`

```
Хеш: Байты
```

Хеш ключа.

Переопределение: [Хеш](../../wiki/security/useraccesskey-object-ru-f7f4bf3f4462.md)

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление в виде имен и значений параметров ключа доступа.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### ВычисляемыйКлючДоступа.Объект

[Пересчитать](../../wiki/security/computableaccesskey-object-ru-0d0b5f774cb0.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/security/useraccesskey-object-ru-f7f4bf3f4462.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных событий

### КлючДоступа.Объект

[Хеш](../../wiki/security/accesskey-object-ru-4c5322ab4636.md)
