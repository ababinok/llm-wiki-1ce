# ВычисляемыйКлючДоступа

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccessControl/ComputableAccessKey_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/AccessControl/ComputableAccessKey_ru/index.html
> SHA256: d23e58cdc86d64545ab25ae6a5a99eab844ecf9b6fbc444f46db436e997252e8
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 10.0 и выше`

`Стд::КонтрольДоступа::ВычисляемыйКлючДоступа` `Доступность: Сервер`

Менеджер вычисляемого ключа доступа.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [КлючДоступа](../../wiki/security/accesskey-ru-10faf3f17fff.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Одиночка](../../wiki/stdlib/singleton-ru-cb90fb36f1e3.md)

*Дочерние типы:* [ИмяВычисляемогоКлючаДоступа](../../wiki/security/computableaccesskeyname-ru-ab6483a7029c.md), [КлючДоступаДляАутентифицированных](../../wiki/security/accesskeyforauthenticated-ru-10a3076a3d4e.md), [КлючДоступаДляВсех](../../wiki/security/accesskeyforeveryone-ru-4a12798615d1.md), [КлючДоступаПользователя](../../wiki/security/useraccesskey-ru-3d9e14563e1e.md)

---

## Методы

### ПересчитатьКлючи

`Доступность: Сервер`

```
ПересчитатьКлючи(Пользователи: ЧитаемыйМассив<Пользователи.Ссылка>? = Неопределено)
```

Пересчитывает все ключи доступа соответствующего типа для пользователей

`Пользователи`

. Если

`Неопределено`

- пересчитывает для всех пользователей.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
