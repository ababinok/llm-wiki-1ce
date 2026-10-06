# Как включить отладку на сервере

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [enable-debugging-on-server-5ff1a4a6d054-ef3d067b17997646](../../raw/text-10.0/enable-debugging-on-server-5ff1a4a6d054-ef3d067b17997646.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Как включить отладку на сервере`, `enable-debugging-on-server`.

## Обзор

Чтобы включить отладку на сервере и в браузере, выполните следующие действия:

## Документированный контракт и примеры

Чтобы включить отладку на сервере и в браузере, выполните следующие действия:

1. На сервере в файле
  
  [debug.yml](https://1cmycloud.com/console/help/element/10.0/docs/topics/server-debug-file/)
  
  разрешите отладку:
  
  `enabled: true`
  
  .
2. [Перезапустите](https://1cmycloud.com/console/help/element/10.0/docs/topics/restart-server/)
  
  сервер.
3. [Откройте](open-app-in-ide-2c0162ac1160.md)
  
  приложение в среде разработки.
4. Нажмите
  
  F5
  
  , чтобы запустить отладку.

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Как включить отладку на сервере](https://1cmycloud.com/console/help/element/10.0/docs/topics/enable-debugging-on-server/).
