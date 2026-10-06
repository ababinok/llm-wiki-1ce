# СтроковыйПотокЗаписи

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/InputOutput/StringWritableStream_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/InputOutput/StringWritableStream_ru/index.html
> SHA256: 2ea76801c2c6b788000c8027b59a3f5dd0982916e47cfd6d6ae9d15e09822764
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::ВводВывод::СтроковыйПотокЗаписи` `Доступность: Сервер`

Поток записи данных в строку. Хранит данные в памяти, не требует явного закрытия.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Закрываемое](../../wiki/stdlib/closeable-ru-67cd73fca69d.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ПотокЗаписи](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ПрочитатьСтроковыйПотокЗаписи(): Строка
    исп Поток = новый СтроковыйПотокЗаписи()
    
    Поток
        .Записать(Байты{74657374})
        .Записать("stream")
	
    возврат Поток.ВСтроку()
;
```

Результат:

```text
teststream
```

---

## Конструкторы

### СтроковыйПотокЗаписи

`Доступность: Сервер`

```
СтроковыйПотокЗаписи()
```

Создает поток записи данных в строку.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строку с данными из потока.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

**Перегрузка** [ВСтроку(Кодировка: Кодировка|Строка): Строка](../../wiki/stdlib/stringwritablestream-ru-60a519728c66.md)

---

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(Кодировка: Кодировка|Строка): Строка
```

Возвращает строку с данными из потока в указанной кодировке.

**Перегрузка** [ВСтроку(): Строка](../../wiki/stdlib/stringwritablestream-ru-60a519728c66.md)

---

### Закрыть

`Доступность: Сервер`

```
Закрыть()
```

Закрывает поток.

**Переопределение** [ПотокЗаписи::Закрыть](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

---

## Список унаследованных методов

### Закрываемое

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/stdlib/stringwritablestream-ru-60a519728c66.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ПотокЗаписи

[Закрыть](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md) [(Переопределение)](../../wiki/stdlib/stringwritablestream-ru-60a519728c66.md)

[Записать](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

[Записать](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)

[СброситьБуферы](../../wiki/stdlib/writablestream-ru-db9a09ef1933.md)
