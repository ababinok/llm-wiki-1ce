# ИсключениеFtp

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [ftpexception-ru-132dadd916c0-6e2648dc27ee15fa](../../raw/text_10_0/ftpexception-ru-132dadd916c0-6e2648dc27ee15fa.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / Ftp.

Имена для поиска: `ИсключениеFtp`, `FtpException`, `Стд::Ftp::ИсключениеFtp`, `Std::Ftp::FtpException`.

## Обзор

Исключение работы по протоколу FTP.

## Документированный контракт и примеры

`Стд::Ftp::ИсключениеFtp` `Доступность: Сервер`

Исключение работы по протоколу FTP.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Исключение](exception-ru-ed2632721976.md), [Объект](object-ru-9e351f286699.md)

---

## Свойства

### КодОшибки

`Доступность: Сервер` `ТолькоЧтение`

```
КодОшибки: Число?
```

Код ошибки, записанный сервером. Стандартные коды ошибок можно найти здесь: [FTP Error Codes](https://en.wikipedia.org/wiki/List_of_FTP_server_return_codes)

---

## Список унаследованных методов

### Исключение

[ВСтроку](exception-ru-ed2632721976.md)

[Информация](exception-ru-ed2632721976.md)

### Объект

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## Список унаследованных свойств

### Исключение

[Ид](exception-ru-ed2632721976.md), [Описание](exception-ru-ed2632721976.md), [ПодавленныеИсключения](exception-ru-ed2632721976.md), [ПоследовательностьВызовов](exception-ru-ed2632721976.md), [Причина](exception-ru-ed2632721976.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Стд::Ftp — Пространство имён XBSL: Std](ftp-0f2eb1c44972.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [ИсключениеFtp](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Ftp/FtpException_ru/).
