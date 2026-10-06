# Если не открывается среда разработки

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/ide-is-not-opening/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/ide-is-not-opening/index.html
> SHA256: d75bbb2017a8f94f7c576950a8fc5cb0e5a7817d1e7f7f471518ad62bd36216c
> SnapshotCreated: 2026-10-05
> Rendition: verified text

При попытке открыть приложение в среде разработке может возникнуть следующая проблема: прогресс останавливается на 75%.

Это может быть связано с отсутствием библиотеки **libsecret**. При этом файл **ide.log** может содержать ошибку вида:

```text
Error: libsecret-1.so.0: cannot open shared object file: No such file or directory
```

Возможно, данная библиотека не установлена в вашей версии Linux. Убедиться в этом можно с помощью следующей команды:

```bash
apt list --installed | grep libsecret
```

Если библиотека не установлена, установите соответствующий пакет, после чего попробуйте открыть приложение снова.
