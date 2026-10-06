# Файл management-echostmanager.yml

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [server-management-echostmanager-file-a73cbc74bac4-3888bc9f0d03313c](../../raw/text-10.0/server-management-echostmanager-file-a73cbc74bac4-3888bc9f0d03313c.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Файл management-echostmanager.yml`, `server-management-echostmanager-file`.

## Обзор

Этот файл содержит настройки взаимодействия сервера с [«Менеджером хостов внешних компонент»](about-external-component-host-manager-dc52b3ac0dbb.md).

## Документированный контракт и примеры

Этот файл содержит настройки взаимодействия сервера с [«Менеджером хостов внешних компонент»](about-external-component-host-manager-dc52b3ac0dbb.md). Данный файл не создается по умолчанию. Если вы хотите включить использование «Менеджера хостов внешних компонент», добавьте файл **management-echostmanager.yml** с [нужными настройками](server-management-echostmanager-file-a73cbc74bac4.md) в каталог экземпляра сервера:

- Windows
- Linux

```text
C:\ProgramData\1C\1CE\instances\1c-enterprise-element-server-with-ide\config\management-echostmanager.yml
```

## Атрибуты файла

- **enabled**
  
  Признак того, что включено использование «Менеджера хостов внешних компонент». Значение по умолчанию — `false` (выключено).
- **connection-info**
  
  Содержит настройки соединения с «Менеджером хостов внешних компонент».
  
  - **address**
    
    IP-адрес, по которому будет осуществляться взаимодействие с «Менеджером хостов внешних компонент». По умолчанию `127.0.0.1`.
  - **port**
    
    Порт, по которому будет осуществляться взаимодействие с «Менеджером хостов внешних компонент». По умолчанию `4000`.

## Пример файла management-echostmanager.yml

```yaml
management-echostmanager:
  enabled: true
  connection-info:
    address: 127.0.0.1
    port: 4001
```

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Файл management-echostmanager.yml](https://1cmycloud.com/console/help/element/10.0/docs/topics/server-management-echostmanager-file/).
