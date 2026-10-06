# Файл management-echostmanager.yml

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/server-management-echostmanager-file/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/server-management-echostmanager-file/index.html
> SHA256: 1bd54580b6c0b1f92e220f5a9a0d1fe049575aa93f19178902186cb1da6aef15
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Этот файл содержит настройки взаимодействия сервера с [«Менеджером хостов внешних компонент»](../../wiki/project/about-external-component-host-manager-dc52b3ac0dbb.md). Данный файл не создается по умолчанию. Если вы хотите включить использование «Менеджера хостов внешних компонент», добавьте файл **management-echostmanager.yml** с [нужными настройками](../../wiki/project/server-management-echostmanager-file-a73cbc74bac4.md) в каталог экземпляра сервера:

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
