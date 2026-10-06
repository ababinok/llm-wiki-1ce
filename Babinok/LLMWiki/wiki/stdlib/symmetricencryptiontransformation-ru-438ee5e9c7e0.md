# ПреобразованиеСимметричногоШифрования

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [symmetricencryptiontransformation-ru-438ee5e9c7e0-08b9e888cf89d659](../../raw/text-10.0/symmetricencryptiontransformation-ru-438ee5e9c7e0-08b9e888cf89d659.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Cryptography.

Имена для поиска: `ПреобразованиеСимметричногоШифрования`, `SymmetricEncryptionTransformation`, `Стд::Криптография::ПреобразованиеСимметричногоШифрования`, `Std::Cryptography::SymmetricEncryptionTransformation`.

## Обзор

Преобразование симметричного шифрования

## Документированный контракт и примеры

`Стд::Криптография::ПреобразованиеСимметричногоШифрования` `Доступность: КлиентИСервер`

Преобразование симметричного шифрования

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](object-ru-9e351f286699.md), [Перечисление](enum-ru-a7a357b96b4c.md), [Представляемое](presentable-ru-fc7455a0880f.md)

---

## Элементы

## Свойства

### AesEcb

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
AesEcb
```

Преобразование AesEcb поддерживает алгоритм AES в модификации ECB с PKCS5Padding

---

### AesCbc

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
AesCbc
```

Преобразование AesCbc поддерживает алгоритм AES в модификации CBC с PKCS5Padding

---

### DesEcb

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
DesEcb
```

Преобразование DesEcb поддерживает алгоритм DES в модификации ECB с PKCS5Padding

---

### DesCbc

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
DesCbc
```

Преобразование DesCbc поддерживает алгоритм DES в модификации CBC с PKCS5Padding

---

### TripleDesEcb

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
TripleDesEcb
```

Преобразование TripleDesEcb поддерживает алгоритм TripleDes(DESede) в модификации ECB с PKCS5Padding

---

### TripleDesCbc

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
TripleDesCbc
```

Преобразование TripleDesEcb поддерживает алгоритм TripleDes(DESede) в модификации CBС с PKCS5Padding

---

### BlowfishEcb

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
BlowfishEcb
```

Преобразование Blowfish поддерживает алгоритм Blowfish в модификации ECB с PKCS5Padding

---

### Rc2Ecb

`Доступность: КлиентИСервер` `ТолькоЧтение`

```
Rc2Ecb
```

Преобразование RC2 поддерживает алгоритм RC2 в модификации ECB с PKCS5Padding

---

## Список унаследованных методов

### Объект

[ПолучитьТип](object-ru-9e351f286699.md)

### Перечисление

[ВСтроку](enum-ru-a7a357b96b4c.md)

[Представление](enum-ru-a7a357b96b4c.md)

### Представляемое

## Список унаследованных свойств

### Перечисление

[Индекс](enum-ru-a7a357b96b4c.md)

## See Also

- [Навигатор раздела](../security/overview.md)
- [Стд::Криптография — Пространство имён XBSL: Std](cryptography-4df84409a922.md)
- [Ключи доступа и разрешения приложения](../security/access-keys-and-permissions.md)

Оригинал: [ПреобразованиеСимметричногоШифрования](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Cryptography/SymmetricEncryptionTransformation_ru/).
