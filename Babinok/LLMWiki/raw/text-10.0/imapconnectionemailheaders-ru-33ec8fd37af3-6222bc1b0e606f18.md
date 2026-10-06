# ЗаголовкиПисьмаВСоединенииImap

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Email/ImapConnectionEmailHeaders_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Email/ImapConnectionEmailHeaders_ru/index.html
> SHA256: d308e71fe61745b7c7ead49989e4b1cead2b220cc1b27f1c05f7d93e9e025bc4
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ЭлектроннаяПочта::ЗаголовкиПисьмаВСоединенииImap` `Доступность: Сервер`

Заголовки письма в соединении Imap.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [ЗаголовкиПисьмаВСоединении](../../wiki/stdlib/connectionemailheaders-ru-6ba776d45029.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

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

**Переопределение** [ЗаголовкиПисьмаВСоединении::ВСтроку](../../wiki/stdlib/connectionemailheaders-ru-6ba776d45029.md)

---

## Список унаследованных методов

### ЗаголовкиПисьмаВСоединении

[ВСтроку](../../wiki/stdlib/connectionemailheaders-ru-6ba776d45029.md) [(Переопределение)](../../wiki/integration/imapconnectionemailheaders-ru-33ec8fd37af3.md)

### Объект

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### ЗаголовкиПисьмаВСоединении

[Заголовки](../../wiki/stdlib/connectionemailheaders-ru-6ba776d45029.md), [Индекс](../../wiki/stdlib/connectionemailheaders-ru-6ba776d45029.md)
