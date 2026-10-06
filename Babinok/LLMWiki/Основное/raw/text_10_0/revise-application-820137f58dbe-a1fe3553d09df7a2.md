# Как создать копию приложения для доработки

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/revise-application/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/revise-application/index.html
> SHA256: 3c0ab76a5a4636785bb5b3e0908506a3d8e466f60a20ada2f764f0dfd6842da4
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Не рекомендуется вносить изменения непосредственно в то приложение, с которым работают пользователи. В случае ошибки или неудачи работа пользователей будет остановлена, а вам придется срочно возвращать приложение к работоспособному состоянию.

Мы рекомендуем создать копию работающего приложения, доработать ее, а после этого [обновить](../../wiki/project/update-application-6358c99ac8dd.md) работающее приложение. Создать копию работающего приложения можно двумя способами.

## Способ 1

Если для доработки вам не нужны данные, которые содержатся в работающем приложении, или если у вас есть архив проекта работающего приложения, то можно:

- [создать](https://1cmycloud.com/console/help/element/10.0/docs/topics/create-application-from-existing-project/)
  
  приложение из проекта,
- [создать](https://1cmycloud.com/console/help/element/10.0/docs/topics/create-app-from-archive/)
  
  приложение из архива проекта.

## Способ 2

Если для доработки вам нужна полная копия работающего приложения с данными, то тогда:

- [сделайте](https://1cmycloud.com/console/help/element/10.0/docs/topics/back-up-application/)
  
  резервную копию приложения (без списка пользователей),
- затем
  
  [создайте](https://1cmycloud.com/console/help/element/10.0/docs/topics/create-app-from-backup/)
  
  приложение из выгрузки.

Не забудьте включить режим разработки для создаваемого приложения. Подробнее смотрите в данной статье: [Как включить режим разработки приложения в панели управления](../../wiki/project/enable-development-mode-a5c31499eca5.md).
