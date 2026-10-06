# ХранилищеКриптоПро

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Cryptography/CryptoProStore_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Cryptography/CryptoProStore_ru/index.html
> SHA256: e60e258df2097511a140e34b78eee11b15d1ba8b46ccb0475492b281d7e58791
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Криптография::ХранилищеКриптоПро` `Доступность: Сервер`

Хранилище сертификатов и ключей шифрования КриптоПро.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ХранилищеКлючей](../../wiki/data/keystore-ru-d23b0ab7f855.md), [ХранилищеСертификатов](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

---

## Примеры

**Общие примеры**

```xbsl
метод ВычислитьПодпись(Данные: Байты, ПсевдонимКлюча: Строка, Секрет: Строка): Байты
    знч Криптопровайдер = Криптография.ПолучитьКриптоПро()
    знч Хранилище = новый ХранилищеКриптоПро()

    знч Ключ = Хранилище.НайтиЗакрытыйКлюч(ПсевдонимКлюча, Секрет)
    знч Сертификат = Хранилище.НайтиСертификат(ПсевдонимКлюча)

    знч Вычислитель = новый ВычислительПодписи(Криптопровайдер, Сертификат, Ключ)
    Вычислитель.УстановитьСлужбуШтамповВремени("http://qs.cryptopro.ru/tsp/tsp.srf")
    
    возврат Вычислитель.Подписать(Данные)
;
```

---

## Конструкторы

### ХранилищеКриптоПро

`Доступность: Сервер`

```
ХранилищеКриптоПро(ТипХранилища: Строка = "HDImageStore")
```

Создает экземпляр объекта для доступа к хранилищу КриптоПро указанного типа

`ТипХранилища`

.

Имя типа хранилища должно соответствовать JCA-спецификации криптопровайдера.

КриптоПро JCP:

- имя "HDImageStore" определяет жесткий диск;
- имя "FloppyStore" определяет дискету;
- имена "OCFStore", "J6CFStore" определяют карточки.

КриптоПро Java CSP (JCSP):

- имя "HDIMAGE" определяет жесткий диск:
- имя "REGISTRY" определяет реестр (в случае ОС Windows).

#### Исключения

**[ИсключениеКриптографии](../../wiki/stdlib/cryptoexception-ru-9269fbee8009.md)** - при ошибке загрузки хранилища.

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ХранилищеКлючей

[ДобавитьЗакрытыйКлюч](../../wiki/data/keystore-ru-d23b0ab7f855.md)

[ДобавитьСертификат](../../wiki/data/keystore-ru-d23b0ab7f855.md)

[НайтиЗакрытыйКлюч](../../wiki/data/keystore-ru-d23b0ab7f855.md)

[Удалить](../../wiki/data/keystore-ru-d23b0ab7f855.md)

### ХранилищеСертификатов

[НайтиПоОтпечатку](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[НайтиПоСерийномуНомеру](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[НайтиПоСубъекту](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[НайтиСертификат](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[ПолучитьПсевдонимы](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[ПолучитьСертификаты](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[Размер](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[Содержит](../../wiki/data/certificatestore-ru-4906eaa48a35.md)
