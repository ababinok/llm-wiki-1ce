# ОписаниеВнешнейСистемыВзаимодействия

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/CollaborationSystem/ExternalCollaborationSystemDescription_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/CollaborationSystem/ExternalCollaborationSystemDescription_ru/index.html
> SHA256: aed133c5965faae26efb7f9b03c77baef788efef0b80aadf6e6b7ed0ae4ef714
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::СистемаВзаимодействия::ОписаниеВнешнейСистемыВзаимодействия` `Доступность: Сервер`

Описание внешней системы системы взаимодействия.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Свойства

### ВидВнешнейСистемы

`Доступность: Сервер` `ТолькоЧтение`

```
ВидВнешнейСистемы: Строка
```

Вид внешней системы системы взаимодействия: "Telegram", "WhatsApp", "WebChat" итд

---

### ОписанияПараметров

`Доступность: Сервер` `ТолькоЧтение`

```
ОписанияПараметров: ЧитаемыйМассив<ОписаниеПараметраВнешнейСистемыВзаимодействия>
```

Массив описаний параметров внешней системы.

---

## Методы

### ВСтроку

`Доступность: Сервер`

```
ВСтроку(): Строка
```

Возвращает строковое представление описания внешней системы.

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/integration/externalcollaborationsystemdescription-ru-6c1f235070df.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)
