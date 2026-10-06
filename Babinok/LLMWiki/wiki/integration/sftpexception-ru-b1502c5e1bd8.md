# ИсключениеSftp

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [sftpexception-ru-b1502c5e1bd8-55c50dc44d95ca3b](../../raw/text-10.0/sftpexception-ru-b1502c5e1bd8-55c50dc44d95ca3b.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Ssh.

Имена для поиска: `ИсключениеSftp`, `SftpException`, `Стд::Ssh::ИсключениеSftp`, `Std::Ssh::SftpException`.

## Обзор

Исключение работы по протоколу SFTP.

## Документированный контракт и примеры

`Стд::Ssh::ИсключениеSftp` `Доступность: Сервер`

Исключение работы по протоколу SFTP.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](../stdlib/exception-ru-ed2632721976.md), [Объект](../stdlib/object-ru-9e351f286699.md)

*Дочерние типы:* [ИсключениеФайловойСистемыSftp](sftpfilesystemexception-ru-90f123104919.md)

---

## Свойства

### КодОшибки

`Доступность: Сервер` `ТолькоЧтение`

```
КодОшибки: Число
```

Код ошибки, записанный сервером. Стандартные коды ошибок можно найти здесь: [SFTP Error Codes](https://winscp.net/eng/docs/sftp_codes).

---

## Список унаследованных методов

### Исключение

[ВСтроку](../stdlib/exception-ru-ed2632721976.md)

[Информация](../stdlib/exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](../stdlib/object-ru-9e351f286699.md)

[Представление](../stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](../stdlib/exception-ru-ed2632721976.md), [Описание](../stdlib/exception-ru-ed2632721976.md), [ПодавленныеИсключения](../stdlib/exception-ru-ed2632721976.md), [ПоследовательностьВызовов](../stdlib/exception-ru-ed2632721976.md), [Причина](../stdlib/exception-ru-ed2632721976.md)

## See Also

- [Навигатор раздела](overview.md)
- [Стд::Ssh — Пространство имён XBSL: Std](ssh-a87cdb6779a9.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [ИсключениеSftp](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Ssh/SftpException_ru/).
