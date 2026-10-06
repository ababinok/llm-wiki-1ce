# СправочникИнформационныхСистем.Ссылка

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrationBus/InformationSystemsCatalog.Reference_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/IntegrationBus/InformationSystemsCatalog.Reference_ru/index.html
> SHA256: d90d0470922697d864888da69b06f54dd92e41aef67bd51d27043bce64b2104c
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Версия 8.0 и выше`

`Стд::ИнтеграционнаяШина::СправочникИнформационныхСистем.Ссылка` `Доступность: КлиентИСервер`

Тип ссылки контракта справочника информационных систем.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [Представляемое](../../wiki/stdlib/presentable-ru-fc7455a0880f.md), [Сущность.Ключ](../../wiki/data/entity-key-ru-7032eabc056b.md), [Сущность.Ссылка](../../wiki/data/entity-reference-ru-d0485ecb981e.md)

---

## Свойства

### Ид

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Ид: Ууид
```

Значение идентификатора ссылки.

Переопределение: [Ид](../../wiki/integration/informationsystemscatalog-reference-ru-257ca2273cc7.md)

---

## Методы

### ВСтроку

`Доступность: КлиентИСервер`

```
ВСтроку(): Строка
```

**Переопределение** [Объект::ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

---

### ЗагрузитьОбъект

`Доступность: Сервер`

```
ЗагрузитьОбъект(Заблокировать: Булево = Ложь): СправочникИнформационныхСистем.Объект?
```

Загружает объект из базы данных по текущей ссылке.

`Заблокировать` - признак необходимости установить блокировку на загружаемый объект до окончания текущей транзакции. Если объекта по ссылке не существует, возвращает `Неопределено`.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md) [(Переопределение)](../../wiki/integration/informationsystemscatalog-reference-ru-257ca2273cc7.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

### Представляемое

[Представление](../../wiki/stdlib/presentable-ru-fc7455a0880f.md)
