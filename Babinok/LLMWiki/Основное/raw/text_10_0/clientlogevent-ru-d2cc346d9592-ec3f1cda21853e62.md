# СобытиеЛогКлиента

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Interface/Events/ClientLogEvent_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Interface/Events/ClientLogEvent_ru/index.html
> SHA256: 0d36a840d238381dc9b6edf2d871999d3158fd78be44030addd5abbb1074bb1e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Интерфейс::События::СобытиеЛогКлиента` `Доступность: Сервер`

При помощи данного события в журнал событий регистрируются сообщения из клиентского лога.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### UserAgent

`Доступность: Сервер` `ТолькоЧтение`

```
UserAgent: Строка?
```

Пользовательский агент

---

### ВидПлатформы

`Доступность: Сервер` `ТолькоЧтение`

```
ВидПлатформы: Строка?
```

Тип платформы

---

### ДатаСобытия

`Доступность: Сервер` `ТолькоЧтение`

```
ДатаСобытия: Момент?
```

Момент возникновения регистрируемого события

---

### ИдКлиента

`Доступность: Сервер` `ТолькоЧтение`

```
ИдКлиента: Строка?
```

Идентификатор клиента

---

### ИмяЛогера

`Доступность: Сервер` `ТолькоЧтение`

```
ИмяЛогера: Строка?
```

Имя логера

---

### Сообщение

`Доступность: Сервер` `ТолькоЧтение`

```
Сообщение: Строка?
```

Логируемое сообщение

---

### УровеньЛогирования

`Доступность: Сервер` `ТолькоЧтение`

```
УровеньЛогирования: Строка?
```

Уровень логирования

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Представляемое

### СобытиеЖурналаСобытий

[ПолучитьСвойство](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

[Представление](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

## Список унаследованных свойств

### СобытиеЖурналаСобытий

[Важность](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ВидСобытия](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Длительность](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Ид](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ИдОшибки](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Имя](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ИнформацияОВнутреннемИсключении](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [КонецОперации](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Момент](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Операции](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Описание](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ОписанияСвойств](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Родитель](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Свойства](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [Успешно](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md), [ХарактерОшибки](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)
