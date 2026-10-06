# Установка «1С:Предприятие.Элемента»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/install-1c-element/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/install-1c-element/index.html
> SHA256: de02ce2d26dcc10004fc17f1975868b6d6e8ca0a77952ded40da7abee3e80516
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Чтобы установить «1С:Предприятие.Элемент», выполните следующие действия:

- Установите систему управления базами данных (СУБД). Вы можете использовать
  
  [PostgreSQL](https://1cmycloud.com/console/help/element/10.0/docs/topics/install-and-configure-postgresql/)
  
  ,
  
  [Tantor SE-1C](https://docs.tantorlabs.ru/tdb/ru/16_8/se1c/intro-whatis.html)
  
  или
  
  [Microsoft SQL Server](https://1cmycloud.com/console/help/element/10.0/docs/topics/microsoft-sql-server/)
  
  .
- Сервер:
  
  - [установите](../../wiki/project/server-installer-d7f9b9f75941.md)
    
    и запустите сервер;
  - [настройте](https://1cmycloud.com/console/help/element/10.0/docs/topics/server-network-settings/)
    
    сетевую конфигурацию;
  - [проверьте](https://1cmycloud.com/console/help/element/10.0/docs/topics/functionality-check/)
    
    работоспособность;
  - [измените](https://1cmycloud.com/console/help/element/10.0/docs/topics/change-administrator-password/)
    
    пароль администратора.
- [Установите](https://1cmycloud.com/console/help/element/10.0/docs/topics/nginx/)
  
  и настройте обратный прокси-сервер.
- [Подключите](https://1cmycloud.com/console/help/element/10.0/docs/topics/connect-database-to-server/)
  
  СУБД к серверу.
- При необходимости:
  
  - [подключите](https://1cmycloud.com/console/help/element/10.0/docs/topics/add-binary-data-storage-to-server/)
    
    дополнительные хранилища двоичных данных к серверу;
  - [установите](https://1cmycloud.com/console/help/element/10.0/docs/topics/cryptography-modules/)
    
    модули криптографии на сервере, чтобы приложения могли использовать электронную подпись;
  - [установите](../../wiki/project/git-installation-9f5d34603556.md)
    
    систему контроля версий Git, чтобы использовать основные возможности групповой разработки приложений;
  - [установите](../../wiki/project/gitlab-installation-48e5e0c558d7.md)
    
    локальную систему управления репозиториями GitLab или подключитесь к облачному GitLab, чтобы использовать полные возможности групповой разработки;
  - [установите](../../wiki/project/install-external-component-host-manager-e43cb4411eb9.md)
    
    «Менеджер хостов внешних компонент» для изолированного выполнения кода системных нативных библиотек, используемых в
    
    «1С:Предприятие.Элементе»
    
    .
