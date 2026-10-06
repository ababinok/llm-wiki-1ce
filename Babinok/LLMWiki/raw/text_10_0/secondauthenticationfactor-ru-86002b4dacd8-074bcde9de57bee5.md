# ВторойФакторАутентификации

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Users/SecondAuthenticationFactor_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Users/SecondAuthenticationFactor_ru/index.html
> SHA256: 34de66c2b99fdf3356418360ec79ebadf4b84c1263b583676b6d7bfcc435b69d
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Пользователи::ВторойФакторАутентификации` `Доступность: КлиентИСервер`

Способ входа вторым фактором.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ВторойФакторАутентификацииПочта](../../wiki/security/secondauthenticationfactoremail-ru-c6ebe097c1b1.md), [ВторойФакторАутентификацииСмс](../../wiki/security/secondauthenticationfactorsms-ru-e9643f6730df.md)

---

## Методы

### Почта

`Доступность: КлиентИСервер` `Статический`

```
Почта(): ВторойФакторАутентификацииПочта
```

Создает настроенный экземпляр способа второго фактора с помощью отправки одноразового кода на электронную почту.

---

### Смс

`Доступность: КлиентИСервер` `Статический`

```
Смс(): ВторойФакторАутентификацииСмс
```

Создает настроенный экземпляр способа второго фактора с помощью отправки одноразового кода по смс.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
