# ПотокЗаписи

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/InputOutput/WritableStream_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/InputOutput/WritableStream_ru/index.html
> SHA256: cad1c0c51198cb29de83205e72799ed9bacaff743254163edf966992b1973056
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ВводВывод::ПотокЗаписи` `Доступность: Сервер`

Однонаправленный поток записи двоичных данных.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Закрываемое](../../wiki/stdlib/closeable-ru-67cd73fca69d.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ВременныйПотокЗаписи](../../wiki/stdlib/temporarywritablestream-ru-402408acf5bc.md), [СтроковыйПотокЗаписи](../../wiki/stdlib/stringwritablestream-ru-60a519728c66.md)

---

## Методы

### Закрыть

`Доступность: Сервер`

```
Закрыть()
```

Закрывает поток.

**Переопределение** [Закрываемое::Закрыть](../../wiki/stdlib/closeable-ru-67cd73fca69d.md)

---

### Записать

`Доступность: Сервер`

```
Записать(Байты: Байты): ПотокЗаписи
```

Записывает в поток байты

`Байты`

. Возвращает текущий поток записи.

**Перегрузка** [Записать(Текст: Строка, Кодировка: Кодировка|Строка = Кодировка.Utf8): ПотокЗаписи](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

---

### Записать

`Доступность: Сервер`

```
Записать(
  Текст: Строка,
  Кодировка: Кодировка|Строка = Кодировка.Utf8
): ПотокЗаписи
```

Записывает в поток строку

`Текст`

в указанной кодировке. Возвращает текущий поток записи.

**Перегрузка** [Записать(Байты: Байты): ПотокЗаписи](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

---

### СброситьБуферы

`Доступность: Сервер`

```
СброситьБуферы()
```

Сбрасывает буфер потока.

---

## Список унаследованных методов

### Закрываемое

[Закрыть](../../wiki/stdlib/closeable-ru-67cd73fca69d.md) [(Переопределение)](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
