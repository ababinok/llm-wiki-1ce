# СтатусПодтверждаемойОперацииСамообслуживания

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Users/SelfService/ConfirmingSelfServiceOperationStatus_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Users/SelfService/ConfirmingSelfServiceOperationStatus_ru/index.html
> SHA256: 0eeeffcd9997ce6a9abc56d527494b3a777ab4a9686ec4beb39d99401d11076b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Пользователи::Самообслуживание::СтатусПодтверждаемойОперацииСамообслуживания` `Доступность: Клиент`

Статус операции самообслуживания требующей подтверждение.

**Сравнение**

Структурное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [СтатусОперацииСамообслуживания](../../wiki/stdlib/selfserviceoperationstatus-ru-40bebaca20fc.md)

---

## Свойства

### МожноПереотправить

`Доступность: Клиент` `ТолькоЧтение`

```
МожноПереотправить: Булево
```

Возможно ли отправить код подтверждения ещё раз.

---

### МоментПовторнойОтправкиКода

`Доступность: Клиент` `ТолькоЧтение`

```
МоментПовторнойОтправкиКода: Момент?
```

Момент когда можно выполнить повторную отправку кода подтверждения.

---

### ОставшиесяПопытки

`Доступность: Клиент` `ТолькоЧтение`

```
ОставшиесяПопытки: Число
```

Оставшееся количество попыток отправки кода подтверждения.

---

### СпособПодтверждения

`Доступность: Клиент` `ТолькоЧтение`

```
СпособПодтверждения: СпособПодтвержденияОперации
```

Способ, которым можно подтвердить операцию.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### СтатусОперацииСамообслуживания

[ПараметрыСОшибками](../../wiki/stdlib/selfserviceoperationstatus-ru-40bebaca20fc.md), [ПредыдущийШагУспешен](../../wiki/stdlib/selfserviceoperationstatus-ru-40bebaca20fc.md), [Сообщение](../../wiki/stdlib/selfserviceoperationstatus-ru-40bebaca20fc.md), [Шаг](../../wiki/stdlib/selfserviceoperationstatus-ru-40bebaca20fc.md)
