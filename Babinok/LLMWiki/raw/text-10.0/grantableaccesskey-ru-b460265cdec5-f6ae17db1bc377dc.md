# ВыдаваемыйКлючДоступа

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccessControl/GrantableAccessKey_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccessControl/GrantableAccessKey_ru/index.html
> SHA256: 527b03bd613a3cbbeb0ae0ebd857da0fa1ef8d721cf6702299581149c3cf5047
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 10.0 и выше`

`Стд::КонтрольДоступа::ВыдаваемыйКлючДоступа` `Доступность: Сервер`

Менеджер выдаваемого ключа доступа.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [КлючДоступа](../../wiki/security/accesskey-ru-10faf3f17fff.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

*Дочерние типы:* [ИмяВыдаваемогоКлючаДоступа](../../wiki/security/grantableaccesskeyname-ru-ef1ca4a7c1cf.md)

---

## Методы

### ОтозватьКлючи

`Доступность: Сервер`

```
ОтозватьКлючи(Пользователи: ЧитаемаяКоллекция<Пользователи.Ссылка>? = Неопределено)
```

Отзывает все ключи доступа соответствующего типа у пользователей

`Пользователи`

. Если

`Неопределено`

- отзывает у всех пользователей и выполняет удаление всех записей из основной таблицы ключа доступа.

#### Исключения

**[ИсключениеДоступЗапрещен](../../wiki/stdlib/accessdeniedexception-ru-f679f509f3e4.md)** - если текущий пользователь не является администратором (или не включен привилегированный режим).

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
