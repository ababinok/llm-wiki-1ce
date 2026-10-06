# ВычисляемыйКлючДоступа.Объект

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [computableaccesskey-object-ru-0d0b5f774cb0-a2922e37fe3b9525](../../raw/text-10.0/computableaccesskey-object-ru-0d0b5f774cb0-a2922e37fe3b9525.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / AccessControl.

Имена для поиска: `ВычисляемыйКлючДоступа.Объект`, `ComputableAccessKey.Object`, `Стд::КонтрольДоступа::ВычисляемыйКлючДоступа.Объект`, `Std::AccessControl::ComputableAccessKey.Object`.

## Обзор

*Базовые типы:* [КлючДоступа.Объект](accesskey-object-ru-4c5322ab4636.md), [Объект](../stdlib/object-ru-9e351f286699.md)

## Документированный контракт и примеры

`Версия 10.0 и выше`

`Стд::КонтрольДоступа::ВычисляемыйКлючДоступа.Объект` `Доступность: Сервер`

Вычисляемый ключ доступа.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [КлючДоступа.Объект](accesskey-object-ru-4c5322ab4636.md), [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИмяВычисляемогоКлючаДоступа.Объект](computableaccesskeyname-object-ru-513b36fec08b.md), [КлючДоступаДляАутентифицированных.Объект](accesskeyforauthenticated-object-ru-edf89a8edefb.md), [КлючДоступаДляВсех.Объект](accesskeyforeveryone-object-ru-0d9da28c0d22.md), [КлючДоступаПользователя.Объект](useraccesskey-object-ru-f7f4bf3f4462.md)

---

## Методы

### Пересчитать

`Доступность: Сервер`

```
Пересчитать(Пользователи: ЧитаемыйМассив<Пользователи.Ссылка>? = Неопределено)
```

Пересчитывает ключ для пользователей

`Пользователи`

. Если

`Неопределено`

- пересчитывает для всех пользователей.

---

## Список унаследованных методов

### Объект

[ВСтроку](../stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### КлючДоступа.Объект

[Хеш](accesskey-object-ru-4c5322ab4636.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::КонтрольДоступа — Пространство имён XBSL: Std](../stdlib/accesscontrol-edf22e1f0a3d.md)
- [Ключи доступа и разрешения приложения](access-keys-and-permissions.md)

Оригинал: [ВычисляемыйКлючДоступа.Объект](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/AccessControl/ComputableAccessKey.Object_ru/).
