# Установка «1С:Предприятие.Элемента»

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [install-1c-element-9ad60130ab46-3c313dcbe6632bd0](../../raw/text-10.0/install-1c-element-9ad60130ab46-3c313dcbe6632bd0.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Установка «1С:Предприятие.Элемента»`, `install-1c-element`.

## Обзор

Чтобы установить «1С:Предприятие.Элемент», выполните следующие действия:

## Документированный контракт и примеры

Чтобы установить «1С:Предприятие.Элемент», выполните следующие действия:

- Установите систему управления базами данных (СУБД). Вы можете использовать
  
  [PostgreSQL](https://1cmycloud.com/console/help/element/10.0/docs/topics/install-and-configure-postgresql/)
  
  ,
  
  [Tantor SE-1C](https://docs.tantorlabs.ru/tdb/ru/16_8/se1c/intro-whatis.html)
  
  или
  
  [Microsoft SQL Server](https://1cmycloud.com/console/help/element/10.0/docs/topics/microsoft-sql-server/)
  
  .
- Сервер:
  
  - [установите](server-installer-d7f9b9f75941.md)
    
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
  - [установите](git-installation-9f5d34603556.md)
    
    систему контроля версий Git, чтобы использовать основные возможности групповой разработки приложений;
  - [установите](gitlab-installation-48e5e0c558d7.md)
    
    локальную систему управления репозиториями GitLab или подключитесь к облачному GitLab, чтобы использовать полные возможности групповой разработки;
  - [установите](install-external-component-host-manager-e43cb4411eb9.md)
    
    «Менеджер хостов внешних компонент» для изолированного выполнения кода системных нативных библиотек, используемых в
    
    «1С:Предприятие.Элементе»
    
    .

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Установка «1С:Предприятие.Элемента»](https://1cmycloud.com/console/help/element/10.0/docs/topics/install-1c-element/).
