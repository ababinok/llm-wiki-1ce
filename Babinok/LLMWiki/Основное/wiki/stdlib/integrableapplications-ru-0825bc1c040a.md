# ИнтегрируемыеПриложения

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrableapplications-ru-0825bc1c040a-3cb450a7577c2be7](../../raw/text-10.0/integrableapplications-ru-0825bc1c040a-3cb450a7577c2be7.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Программный тип XBSL.

Владелец: Std / IntegrableApplications.

Имена для поиска: `ИнтегрируемыеПриложения`, `IntegrableApplications`, `Стд::ИнтегрируемыеПриложения::ИнтегрируемыеПриложения`, `Std::IntegrableApplications::IntegrableApplications`.

## Обзор

Менеджер всех интегрируемых приложений в приложении.

## Документированный контракт и примеры

`Стд::ИнтегрируемыеПриложения::ИнтегрируемыеПриложения` `Тип-одиночка` `Доступность: Сервер`

Менеджер всех интегрируемых приложений в приложении.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Обходимое<ИнтегрируемоеПриложение>](iterable-ru-283adb0cc9eb.md), [Объект](object-ru-9e351f286699.md), [Объект](object-ru-9e351f286699.md), [Одиночка](singleton-ru-cb90fb36f1e3.md)

---

## Примеры

**Общие примеры**

```xbsl
для ИнтегрируемоеПриложение из ИнтегрируемыеПриложения
    ИнтегрируемоеПриложение.ПересчитатьРазрешенияДоступа()
    ИнтегрируемоеПриложение.ПересчитатьРазрешенияДоступаДляОбъектов()
;     
```

---

## Список унаследованных методов

### Обходимое

[ВМассив](iterable-ru-283adb0cc9eb.md)

[ВСоответствие](iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСКлючами](iterable-ru-283adb0cc9eb.md)

[ВСоответствиеСоЗначениями](iterable-ru-283adb0cc9eb.md)

[ВоМножество](iterable-ru-283adb0cc9eb.md)

[ВсеСоответствуют](iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](iterable-ru-283adb0cc9eb.md)

[ГруппироватьПо](iterable-ru-283adb0cc9eb.md)

[ДляКаждого](iterable-ru-283adb0cc9eb.md)

[ДляКаждого](iterable-ru-283adb0cc9eb.md)

[Единственный](iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиНеопределено](iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ЕдинственныйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ЕстьСоответствия](iterable-ru-283adb0cc9eb.md)

[КакПоследовательность](iterable-ru-283adb0cc9eb.md)

[Максимум](iterable-ru-283adb0cc9eb.md)

[МаксимумПо](iterable-ru-283adb0cc9eb.md)

[Минимум](iterable-ru-283adb0cc9eb.md)

[МинимумПо](iterable-ru-283adb0cc9eb.md)

[НетСоответствий](iterable-ru-283adb0cc9eb.md)

[Объединить](iterable-ru-283adb0cc9eb.md)

[Объединить](iterable-ru-283adb0cc9eb.md)

[Первый](iterable-ru-283adb0cc9eb.md)

[ПервыйИлиНеопределено](iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ПервыйИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[ПотомСортироватьПо](iterable-ru-283adb0cc9eb.md)

[Преобразовать](iterable-ru-283adb0cc9eb.md)

[Преобразовать](iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](iterable-ru-283adb0cc9eb.md)

[ПреобразоватьЛинейно](iterable-ru-283adb0cc9eb.md)

[ПропуститьНеопределено](iterable-ru-283adb0cc9eb.md)

[Пусто](iterable-ru-283adb0cc9eb.md)

[Свернуть](iterable-ru-283adb0cc9eb.md)

[Свернуть](iterable-ru-283adb0cc9eb.md)

[Соединить](iterable-ru-283adb0cc9eb.md)

[Сортировать](iterable-ru-283adb0cc9eb.md)

[Сортировать](iterable-ru-283adb0cc9eb.md)

[СортироватьПо](iterable-ru-283adb0cc9eb.md)

[Среднее](iterable-ru-283adb0cc9eb.md)

[СреднееИлиУмолчание](iterable-ru-283adb0cc9eb.md)

[Сумма](iterable-ru-283adb0cc9eb.md)

[Уникальные](iterable-ru-283adb0cc9eb.md)

[УникальныеПо](iterable-ru-283adb0cc9eb.md)

[Фильтровать](iterable-ru-283adb0cc9eb.md)

[Фильтровать](iterable-ru-283adb0cc9eb.md)

[ФильтроватьПоТипу](iterable-ru-283adb0cc9eb.md)

### Объект

[ВСтроку](object-ru-9e351f286699.md)

[ПолучитьТип](object-ru-9e351f286699.md)

[Представление](object-ru-9e351f286699.md)

## See Also

- [Навигатор раздела](../integration/overview.md)
- [Стд::ИнтегрируемыеПриложения — Пространство имён XBSL: Std](integrableapplications-fb6cab06cdcb.md)
- [HTTP-клиент и обработка JSON](../integration/http-and-json.md)
- [Процессы интеграции и ограничения облака](../integration/integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](../integration/http-json-response-route.md)

Оригинал: [ИнтегрируемыеПриложения](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/IntegrableApplications/IntegrableApplications_ru/).
