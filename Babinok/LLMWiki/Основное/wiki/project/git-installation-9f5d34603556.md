# Установка Git

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [git-installation-9f5d34603556-007fc4fee5cad100](../../raw/text-10.0/git-installation-9f5d34603556-007fc4fee5cad100.md); [6093d2bf4c3d361e518d8da88ed80f8e84db216149f7488e521a9c2f9a2c0cb1-81c4bcbfbec8f525](../../raw/figures/6093d2bf4c3d361e518d8da88ed80f8e84db216149f7488e521a9c2f9a2c0cb1-81c4bcbfbec8f525.md); [3d1d385963d5729d7d3febaa1f98739256ef1f76d5af56bce62297e277fd639d-918e054a848dacf1](../../raw/figures/3d1d385963d5729d7d3febaa1f98739256ef1f76d5af56bce62297e277fd639d-918e054a848dacf1.md); [508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Установка Git`, `git-installation`.

## Обзор

Установка Git показана на примере версии 2.37.0 64-bit (Windows).

## Документированный контракт и примеры

Установка Git показана на примере версии 2.37.0 64-bit (Windows).

## ОС Windows

> [!NOTE] примечание
> В качестве примера используется ОС Windows 10 Pro.

Чтобы установить Git, выполните следующие действия:

1. Перейдите на страницу дистрибутивов Git: [https://git-scm.com/download/win](https://git-scm.com/download/win).
  
  Исторический снимок страницы Git for Windows выделяет раздел Standalone Installer и ссылки «32-bit Git for Windows Setup» и «64-bit Git for Windows Setup». [Описание иллюстрации](../../raw/figures/6093d2bf4c3d361e518d8da88ed80f8e84db216149f7488e521a9c2f9a2c0cb1-81c4bcbfbec8f525.md)
2. Скачайте дистрибутив той разрядности, которая соответствует вашей операционной системе: 32-bit или 64-bit.
3. Запустите его и установите Git, не меняя стандартных настроек.
  
  Окно установщика Git на шаге лицензионного соглашения с кнопкой «Next»; пример сопровождает установку со стандартными настройками. [Описание иллюстрации](../../raw/figures/3d1d385963d5729d7d3febaa1f98739256ef1f76d5af56bce62297e277fd639d-918e054a848dacf1.md)

## Изменение настроек Git в среде разработки

«1С:Предприятие.Элемент» позволяет изменять глобальные настройки значений конфигурации Git. Для этого администратор сервера должен выполнить следующие действия:

1. Открыть консоль от имени пользователя, под учетной записью которого запущен сервер. При локальной установке «Элемента» это пользователь *USR1CE* (*usr1ce*).
2. Выполнить нужные команды. Например, задать имя пользователя и адрес электронной почты:
  
  ```bash
  $ git config --global user.name "Ваше имя"
  $ git config --global user.email yourmail@example.com
  ```

## См. также

- [Настройка Git](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git)


Примечание. [Описание иллюстрации](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Установка Git](https://1cmycloud.com/console/help/element/10.0/docs/topics/git-installation/).
