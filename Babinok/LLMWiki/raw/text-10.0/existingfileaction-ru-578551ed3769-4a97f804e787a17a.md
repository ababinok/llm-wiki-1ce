# ДействиеНадСуществующимФайлом

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/IntegrationProcessSchema/Std/Enums/ExistingFileAction_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/IntegrationProcessSchema/Std/Enums/ExistingFileAction_ru/index.html
> SHA256: b88b6f6fdda0b84462a45c34f576a32fc6fd008715e7e233e62374d15f34a8db
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Что сделает «Элемент», если уже существует файл, в который нужно записать тело сообщения.

---

## Литералы

#### Перезаписывать

Перезапишет существующий файл.

---

#### Дописывать

Допишет тело сообщения в конец существующего файла. Такой файл будет содержать тела нескольких сообщений.

---

#### ВыдаватьОшибку

Не изменит существующий файл и вызовет исключение. Сообщение не будет считаться доставленным.

---

#### Оставлять

Не изменит существующий файл. Сообщение будет считаться доставленным.

---
