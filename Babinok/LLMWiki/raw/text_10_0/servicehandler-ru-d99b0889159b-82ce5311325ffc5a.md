# ОбработчикСервиса

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/SoapService/Handlers/ServiceHandler_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/SoapService/Handlers/ServiceHandler_ru/index.html
> SHA256: 82bb8dd11b7bc7aff393df522b04f477e4cbbc07ff62b92d80e172afc91f12a7
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Описание операции SOAP-сервиса.

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### Метод

```yaml
Метод: Строка
```

Имя метода, который реализует операцию SOAP-сервиса.

---

#### КонтрольДоступа

```yaml
КонтрольДоступа: 
    Разрешения: 
        Вызов: КонтрольДоступа
    Обработчик: Строка
```

Содержит [настройки прав доступа](../../wiki/security/automatically-grant-permissions-to-user-groups-c39cf49a7075.md) для вызова данной операции сервиса. Если значение не указано, то берется значение свойства [КонтрольДоступа](../../wiki/integration/soapservice-33331940c1db.md), заданное для всего SOAP-сервиса.

<details>
<summary>**Свойства**</summary>

##### Разрешения

Набор разрешений на выполнение операции SOAP-сервиса.

<details>
<summary>**Свойства**</summary>

##### Вызов

Возможность вызова данной операции сервиса.

</details>

##### Обработчик

Метод-обработчик, реализующий контроль доступа.

</details>

---

#### Ошибки

```yaml
Ошибки: Тип<Исключение>[]
```

Типы исключений, которые может выбрасывать метод. Если указанный тип не является исключением, возникает ошибка проверки проекта. «1С:Предприятие.Элемент» накладывает [ограничения](../../wiki/integration/soap-service-types-a958b90025c0.md) на типы исключений.

---
