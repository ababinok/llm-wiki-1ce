# Что такое «Менеджер хостов внешних компонент»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/about-external-component-host-manager/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/about-external-component-host-manager/index.html
> SHA256: 4dcd7753b8bd7e40406833d0175ce7920eca3cdb3050dd573022544cb8f1fa32
> SnapshotCreated: 2026-10-05
> Rendition: verified text

«Менеджер хостов внешних компонент» позволяет изолированно, в отдельном процессе, выполнять код системных нативных библиотек, используемых в «1С:Предприятие.Элементе». Например, эти библиотеки используются при работе с такими объектами, как [`ТабличныйДокумент`](../../wiki/stdlib/spreadsheet-ru-1fd2c1039119.md), [`ДокументHtml`](../../wiki/data/htmldocument-ru-fdd3a15c8c8f.md) и [`ПросмотрPDF`](../../wiki/interface/pdfview-ru-5d1a45f50001.md). Использование изолированного хоста предотвращает падение сервера при ошибках во внешних компонентах, а также позволяет более точно отслеживать, анализировать и контролировать потребляемые ресурсы.

Чтобы активировать «Менеджер хостов внешних компонент», выполните следующие действия:

- [установите](../../wiki/project/install-external-component-host-manager-e43cb4411eb9.md)
  
  и
  
  [запустите](../../wiki/project/run-external-component-host-manager-5358c30e708a.md)
  
  «Менеджер хостов внешних компонент»,
- [настройте сетевую конфигурацию менеджера](../../wiki/project/configure-external-component-host-manager-cb0f4f1ddd36.md)
  
  ,
- [проверьте работоспособность менеджера](../../wiki/project/check-external-component-host-manager-69cff5c863b1.md)
  
  ,
- [настройте конфигурационный файл сервера](../../wiki/project/server-management-echostmanager-file-a73cbc74bac4.md)
  
  , чтобы включить использование «Менеджера хостов внешних компонент» в
  
  «1С:Предприятие.Элементе»
  
  .
