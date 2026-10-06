# Удаление сообщений

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/delete-messages/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/delete-messages/index.html
> SHA256: 483bc1c3a3268daab2d66e35cc5c5658ddc118081beb7d478f5634837d6b0ecb
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Для удаления сообщений вы можете использовать метод [`УдалитьСообщение()`](../../wiki/integration/collaborationsystem-ru-51561bd68a2c.md) типа [`СистемаВзаимодействия`](../../wiki/integration/collaborationsystem-ru-51561bd68a2c.md).

Пример удаления сообщения

```xbsl
метод УдалитьСообщениеВзаимодействия()
    знч ИдСообщения = Ууид{520a34cb-f8cb-4c79-ba78-45b7fdfb080d}
    знч Таймаут = 5с

    попытка
        СистемаВзаимодействия.УдалитьСообщение(ИдСообщения, Таймаут)
    поймать Исключение: ИсключениеСистемыВзаимодействия
    // Обработка исключения...
    ;
;
```
