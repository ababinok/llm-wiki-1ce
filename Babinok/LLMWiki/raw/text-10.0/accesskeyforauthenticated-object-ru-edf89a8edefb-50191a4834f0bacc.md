# КлючДоступаДляАутентифицированных.Объект

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccessControl/AccessKeyForAuthenticated.Object_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccessControl/AccessKeyForAuthenticated.Object_ru/index.html
> SHA256: 023db6ad773aef866e77f53e6eb83bb3ad8f2320659b8896fe146916a9c54ecc
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::КонтрольДоступа::КлючДоступаДляАутентифицированных.Объект` `Доступность: Сервер`

Ключ доступа, присутствующий у всех пользователей. Т.е. у всех, исключая анонимных.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ВычисляемыйКлючДоступа.Объект](../../wiki/security/computableaccesskey-object-ru-0d0b5f774cb0.md), [КлючДоступа.Объект](../../wiki/security/accesskey-object-ru-4c5322ab4636.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Конструкторы

### КлючДоступаДляАутентифицированных.Объект

`Доступность: Сервер`

```
КлючДоступаДляАутентифицированных.Объект()
```

Создает ключ доступа для аутентифицированных.

---

## Свойства

### Хеш

`Доступность: Сервер` `ТолькоЧтение`

```
Хеш: Байты
```

Хеш ключа.

Переопределение: [Хеш](../../wiki/security/accesskeyforauthenticated-object-ru-edf89a8edefb.md)

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

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/security/accesskeyforauthenticated-object-ru-edf89a8edefb.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных событий

### КлючДоступа.Объект

[Хеш](../../wiki/security/accesskey-object-ru-4c5322ab4636.md)
