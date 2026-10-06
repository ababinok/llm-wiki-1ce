# Как получить ключ доступа пользователя

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [get-user-key-9b77ae83ecbb-92db75b6d9729c42](../../raw/text_10_0/get-user-key-9b77ae83ecbb-92db75b6d9729c42.md); [0f020fd26492c47e1f482591717ce905950fab4751e1bddfe92f268cc2054148-33b2d4c5efab5d4a](../../raw/figures/0f020fd26492c47e1f482591717ce905950fab4751e1bddfe92f268cc2054148-33b2d4c5efab5d4a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Как получить ключ доступа пользователя`, `get-user-key`.

## Обзор

В «1С:Предприятие.Элементе» существует два основных вида [ключей доступа](https://1cmycloud.com/console/help/element/10.0/docs/topics/user-information-system/): для доступа к приложениям и для доступа к [панели управления](https://1cmycloud.com/console/help/element/10.0/docs/topics/control-panel/).

## Документированный контракт и примеры

В «1С:Предприятие.Элементе» существует два основных вида [ключей доступа](https://1cmycloud.com/console/help/element/10.0/docs/topics/user-information-system/): для доступа к приложениям и для доступа к [панели управления](https://1cmycloud.com/console/help/element/10.0/docs/topics/control-panel/).

Ключи доступа к приложениям используются для получения информации о приложении внешними информационными системами: например, для аутентификации при запросе доступа к HTTP-сервису, сделанным другим приложением или консольной утилитой по расписанию ([подробнее](external-program-authentication-af85e93b18a7.md)).

Ключ доступа к панели управления обеспечивает доступ администраторам и разработчикам приложений к информации о приложениях и проектах, которая хранится на сервере.

## Получение ключа доступа к приложению

Получить [ключ доступа](https://1cmycloud.com/console/help/element/10.0/docs/topics/user-information-system/) пользователя к приложению можно несколькими способами: через [панель управления](get-user-key-9b77ae83ecbb.md), [в коде](get-user-key-9b77ae83ecbb.md) и с помощью [HTTP API](get-user-key-9b77ae83ecbb.md).

### В панели управления

1. [Откройте](https://1cmycloud.com/console/help/element/10.0/docs/topics/open-control-panel/) панель управления.
2. Нажмите **Приложения** и нажмите на нужное приложение.
3. Нажмите **Пользователи** и выберите пользователя.
4. В группе **Ключи доступа** нажмите **+ Получить**.
5. Задайте описание ключа.
6. Скопируйте **Client-ID** и **Client-Secret** в буфер обмена или блокнот.
  
  Окно «Скопируйте ключ доступа» содержит поля Client-ID и Client-Secret. [Описание иллюстрации](../../raw/figures/0f020fd26492c47e1f482591717ce905950fab4751e1bddfe92f268cc2054148-33b2d4c5efab5d4a.md)

### В коде

`ПользователиСервиса.СгенерироватьДанныеЗапросаТокенаДоступа()`

### С помощью HTTP API

- [Создать токен доступа](https://1cmycloud.com/console/help/element/10.0/docs/console/post-console-api-v-2-1-user-lists-user-list-id-users-user-id-access-tokens/)

## Получение ключа доступа к панели управления

Ключ доступа к панели управления используется для [получения токена доступа к API панели управления](https://1cmycloud.com/console/help/element/10.0/docs/console/post-console-sys-token/). Чтобы получить [ключ доступа](https://1cmycloud.com/console/help/element/10.0/docs/topics/user-information-system/) пользователя к панели управления, выполните действия, описанные ниже.

### В панели управления

1. [Откройте](https://1cmycloud.com/console/help/element/10.0/docs/topics/open-control-panel/) панель управления.
2. Откройте профиль.
  
  
3. В группе **Ключи доступа** нажмите **+ Получить**.
4. Задайте описание ключа.
5. Скопируйте **Client-ID** и **Client-Secret** в буфер обмена или блокнот.
  
  Окно «Скопируйте ключ доступа» содержит поля Client-ID и Client-Secret. [Описание иллюстрации](../../raw/figures/0f020fd26492c47e1f482591717ce905950fab4751e1bddfe92f268cc2054148-33b2d4c5efab5d4a.md)

## See Also

- [Навигатор раздела](overview.md)
- [Ключи доступа и разрешения приложения](access-keys-and-permissions.md)

Оригинал: [Как получить ключ доступа пользователя](https://1cmycloud.com/console/help/element/10.0/docs/topics/get-user-key/).
