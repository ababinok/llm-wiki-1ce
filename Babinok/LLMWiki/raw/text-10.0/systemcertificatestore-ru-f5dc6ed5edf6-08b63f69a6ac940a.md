# СистемноеХранилищеСертификатов

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Cryptography/SystemCertificateStore_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Cryptography/SystemCertificateStore_ru/index.html
> SHA256: 2d0ed55ee0d47ccc0517b34dfd9f0588e7888202b3cb3ed212bd4899bb55afee
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Криптография::СистемноеХранилищеСертификатов` `Доступность: КлиентИСервер`

Предоставляет доступ к цифровым сертификатам, установленным в операционной системе.

В зависимости от операционной системы будет использовано хранилище:

- Для macOS, Windows и Android - системное (корневое) хранилище сертификатов (например, для Windows - это
  
  `Windows-ROOT`
  
  ).
- Для Linux расположение хранилища доверенных сертификатов зависит от дистрибутива.
  
  - Все сертификаты, расположенные в каталогах, считаются доверенными:
    
    - Debian, Mint, Ubuntu, CentOS, Fedora, RedHat:
      
      `/etc/ssl/certs`
    - CentOS, Fedora, RedHat (additional):
      
      `/etc/pki/tls/certs/`
    - Alt Linux:
      
      `/etc/share/ca-certificates/`
    - RHEL/SL:
      
      `/etc/pki/ca-trust/source/anchors`
  - Все сертификаты, расположенные в файлах, считаются доверенными:
    
    - OpenSUSE:
      
      `/etc/ssl/ca-bundle.pem`
    - OpenELEC:
      
      `/etc/pki/tls/cacert.pem`
    - CentOS, RHEL 7:
      
      `/etc/pki/ca-trust/extracted/pem/tls-ca-bundle.pem`
    - Alpine Linux:
      
      `/etc/ssl/cert.pem`

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [ХранилищеСертификатов](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

---

## Конструкторы

### СистемноеХранилищеСертификатов

`Версия 8.0 и выше`

`Доступность: Сервер`

```
СистемноеХранилищеСертификатов()
```

Создаёт объект

`СистемноеХранилищеСертификатов`

для доступа к сертификатам.

**Перегрузка** [СистемноеХранилищеСертификатов(ВидХранилища: ВидСистемногоХранилищаСертификатов = ВидСистемногоХранилищаСертификатов.ТекущийПользовательОс, ВидСертификатов: ВидЦифровогоСертификата? = Неопределено, Криптопровайдер: Криптопровайдер? = Неопределено)](../../wiki/data/systemcertificatestore-ru-f5dc6ed5edf6.md)

---

### СистемноеХранилищеСертификатов

`Версия 8.0 и выше`

`Доступность: Клиент`

```
СистемноеХранилищеСертификатов(
  ВидХранилища: ВидСистемногоХранилищаСертификатов = ВидСистемногоХранилищаСертификатов.ТекущийПользовательОс,
  ВидСертификатов: ВидЦифровогоСертификата? = Неопределено,
  Криптопровайдер: Криптопровайдер? = Неопределено)
```

Создаёт объект

`СистемноеХранилищеСертификатов`

для доступа к сертификатам с указанными параметрами. Если

`ВидСертификатов`

=

`Неопределено`

, возвращаются все доступные сертификаты

**Перегрузка** [СистемноеХранилищеСертификатов()](../../wiki/data/systemcertificatestore-ru-f5dc6ed5edf6.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### ХранилищеСертификатов

[НайтиПоОтпечатку](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[НайтиПоСерийномуНомеру](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[НайтиПоСубъекту](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[НайтиСертификат](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[ПолучитьПсевдонимы](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[ПолучитьСертификаты](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[Размер](../../wiki/data/certificatestore-ru-4906eaa48a35.md)

[Содержит](../../wiki/data/certificatestore-ru-4906eaa48a35.md)
