# ОшибкаВалидацииСообщенияПроцессаИнтеграции

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessMessageValidationError_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/IntegrationBus/Events/IntegrationProcessMessageValidationError_ru/index.html
> SHA256: d806b9dc52b136bf6b9283d4e6a3d16614d055b8c173245c8fcd94dd2ae9395b
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ИнтеграционнаяШина::События::ОшибкаВалидацииСообщенияПроцессаИнтеграции` `Доступность: Сервер`

Событие регистрируется при ошибке валидации сообщения, полученного в узле-источнике

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [СобытиеЖурналаСобытий](../../wiki/stdlib/eventlogevent-ru-928cb9b58d56.md)

---

## Свойства

### ИдСообщения

`Доступность: Сервер` `ТолькоЧтение`

```
ИдСообщения: Строка?
```

Идентификатор сообщения с ошибкой.

---

### Ошибка

`Доступность: Сервер` `ТолькоЧтение`

```
Ошибка: Строка?
```

Текст ошибки

---

### Процесс

`Доступность: Сервер` `ТолькоЧтение`

```
Процесс: Строка?
```

Процесс интеграции, в котором было зарегистрировано событие.

---

### Узел

`Доступность: Сервер` `ТолькоЧтение`

```
Узел: Строка?
```

Узел-источник, в котором произошла ошибка.

---

### Участник

`Доступность: Сервер` `ТолькоЧтение`

```
Участник: Строка?
```

Участник, у которого произошла ошибка.

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
