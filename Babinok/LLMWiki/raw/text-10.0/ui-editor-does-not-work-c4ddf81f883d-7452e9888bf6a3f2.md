# Не работает редактор компонентов интерфейса

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/ui-editor-does-not-work/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/ui-editor-does-not-work/index.html
> SHA256: 266e7dd4fc672609ac3761ad676fc657bf55757866b89743a8fece4fd84c9ee6
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Чтобы редактор компонентов интерфейса работал корректно, у пользователя сервера должен быть настроенный SSL-сертификат.

Если SSL-сертификат не настроен, поддерживаются только два адреса сервера: **127.0.0.1** и **localhost**. Если используется собственный адрес, прописанный в файле **hosts**, редактор компонентов интерфейса также работать не будет.
