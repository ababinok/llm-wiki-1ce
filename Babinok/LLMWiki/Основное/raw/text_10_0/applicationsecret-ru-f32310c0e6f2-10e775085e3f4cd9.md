# СекретПриложения

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Security/ApplicationSecret_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Security/ApplicationSecret_ru/index.html
> SHA256: 8f13839cf03595c21b28c4928d31cf4a5a41b8e6362b23ef6f04e8e835cbf0d3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Безопасность::СекретПриложения` `Доступность: КлиентИСервер`

Секрет, общий для приложения

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Секрет](../../wiki/security/secret-ru-be3e2bf29a04.md)

---

## Конструкторы

### СекретПриложения

`Версия 7.0 и выше`

`Доступность: КлиентИСервер`

```
СекретПриложения(Значение: Строка)
```

Создает секрет общий для приложения типа СекретПриложения. Максимальная длина

`Значение`

составляет 1000 символов. Результат - зашифрованное значение.

#### Исключения

**[ИсключениеНедопустимыйАргумент](../../wiki/stdlib/illegalargumentexception-ru-fc532bf88932.md)** - если длина `Значение` более 1000 символов

#### Примеры

```xbsl
    пер Секрет1 = новый СекретПриложения("Секрет1")
    пер ЗначениеОткрытое = Секрет1.Раскрыть()
```

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### Секрет

[Раскрыть](../../wiki/security/secret-ru-be3e2bf29a04.md)
