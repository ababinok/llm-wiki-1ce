# ПисьмоВСоединенииImap

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/ImapConnectionEmail_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Email/ImapConnectionEmail_ru/index.html
> SHA256: b4eefa908e9d0e608c4623b17dce7cd5befafe85c4697e4983517004ad158a32
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ЭлектроннаяПочта::ПисьмоВСоединенииImap` `Доступность: Сервер`

Письмо в соединении Imap с почтовым сервером.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ПисьмоВСоединении](../../wiki/stdlib/connectionemail-ru-3bc736738b66.md)

---

## Свойства

### Uid

`Доступность: Сервер` `ТолькоЧтение`

```
Uid: Число
```

Uid письма. Uid - это уникальное для каталога число, которое монотонно растет от старого письма к новому. В отличии от индекса, значение не обязательно непрерывное. Значение не меняется внутри сессии, а также почтовым серверам рекомендовано не менять данное значение между сессиями. Если идентификатор письма изменяется, то изменился и UIDVALIDITY каталога

---

### Флаги

`Доступность: Сервер` `ТолькоЧтение`

```
Флаги: ЧитаемыйМассив<ФлагПисьма>
```

Флаги письма.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

**Переопределение** [ПисьмоВСоединении::ВСтроку](../../wiki/stdlib/connectionemail-ru-3bc736738b66.md)

---

## Список унаследованных методов

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ПисьмоВСоединении

[ВСтроку](../../wiki/stdlib/connectionemail-ru-3bc736738b66.md) [(Переопределение)](../../wiki/integration/imapconnectionemail-ru-094da2928301.md)

## Список унаследованных свойств

### ПисьмоВСоединении

[Индекс](../../wiki/stdlib/connectionemail-ru-3bc736738b66.md), [НаУдаление](../../wiki/stdlib/connectionemail-ru-3bc736738b66.md), [Письмо](../../wiki/stdlib/connectionemail-ru-3bc736738b66.md)
