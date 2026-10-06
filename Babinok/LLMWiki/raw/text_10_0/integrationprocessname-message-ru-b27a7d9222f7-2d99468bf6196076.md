# {ИмяПроцессаИнтеграции}.Сообщение

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.Message_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/DeveloperName/ProjectName/SubsystemName/IntegrationProcessName.Message_ru/index.html
> SHA256: 1afeace65698dd08b99207f967e676fdc260650c4eeca274b99fe2d43488f4cc
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`{ИмяРазработчика}::{ИмяПроекта}::{ИмяПодсистемы}::{ИмяПроцессаИнтеграции}.Сообщение` `Доступность: Сервер`

Сообщение, передаваемое процессом интеграции.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Объект](../../wiki/stdlib/object-ru-9e351f286699.md), [СообщениеИнтеграции](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

## Свойства

### Отправитель

`Версия 8.0 и выше`

`Доступность: Сервер` `ТолькоЧтение`

```
Отправитель: ИмяИнформационныхСистем.Данные?
```

Данные участника-отправителя сообщения или `Неопределено`, если сообщение отправлено из узла, не связанного с группой участников.

---

### Отправитель

`Версия 7.0 и ниже`

`Доступность: Сервер` `ТолькоЧтение`

```
Отправитель: ИнформационныеСистемы.Данные?
```

Свойство заменено на [Отправитель](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md).

---

### Получатели

`Версия 8.0 и выше`

`Доступность: Сервер` `ТолькоЧтение`

```
Получатели: ЧитаемыйМассив<ИмяИнформационныхСистем.Данные>
```

Данные участников-получателей сообщения. Коды получателей могут быть установлены отправителем сообщения или изменены при помощи метода [УстановитьКодыПолучателей](../../wiki/integration/integrationmessage-ru-379e89488b99.md).

---

### Получатели

`Версия 7.0 и ниже`

`Доступность: Сервер` `ТолькоЧтение`

```
Получатели: ЧитаемыйМассив<ИнформационныеСистемы.Данные>
```

Свойство заменено на [Получатели](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md).

---

### УзлыПути

`Доступность: Сервер` `ТолькоЧтение`

```
УзлыПути: {ИмяПроцессаИнтеграции}.УзлыПути
```

Путь на схеме, который прошло сообщение: узлы и участники-получатели в узлах.

#### Примеры

Пример использования пути, которое прошло сообщения, для выбора имени в узле [ФайлНазначение](../../wiki/integration/integrationschemanodekind-ru-a40f2abdcc09.md).

```xbsl
метод ПриВыбореИмени(Контекст: ФайловыйПроцесс.КонтекстВызова, Сообщение: ФайловыйПроцесс.Сообщение): Строка
    знч КодHttp = Сообщение.УзлыПути.Получить(ФайловыйПроцесс.Схема.Узлы.HttpЗапросКурсовВалют).Получатель.Код
    знч КодТекущий = Сообщение.УзлыПути.Текущий.Получатель.Код
    возврат "%{КодHttp}/%{КодТекущий}/Ответ.json"
;
```

---

## Методы

### Копировать

`Доступность: Сервер`

```
Копировать(): {ИмяПроцессаИнтеграции}.Сообщение
```

**Переопределение** [СообщениеИнтеграции::Копировать](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

### УдалитьПараметр

`Доступность: Сервер`

```
УдалитьПараметр(Имя: Строка): {ИмяПроцессаИнтеграции}.Сообщение
```

Переопределяет метод

[УдалитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

, возвращает сообщение конкретного, а не базового типа.

**Переопределение** [СообщениеИнтеграции::УдалитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

### УстановитьКодыПолучателей

`Доступность: Сервер`

```
УстановитьКодыПолучателей(Значение: ЧитаемыйМассив<Строка>): {ИмяПроцессаИнтеграции}.Сообщение
```

Переопределяет метод

[УстановитьКодыПолучателей](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

, возвращает сообщение конкретного, а не базового типа.

**Переопределение** [СообщениеИнтеграции::УстановитьКодыПолучателей](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

### УстановитьПараметр

`Версия 10.0 и выше`

`Доступность: Сервер`

```
УстановитьПараметр(
  Имя: Строка,
  Значение: Объект|Undefined
): {ИмяПроцессаИнтеграции}.Сообщение
```

Переопределяет метод

[УстановитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

, возвращает сообщение конкретного, а не базового типа.

**Переопределение** [СообщениеИнтеграции::УстановитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

### УстановитьПараметр

`Версия 9.0 и ниже`

`Доступность: Сервер`

```
УстановитьПараметр(
  Имя: Строка,
  Значение: Объект?
): {ИмяПроцессаИнтеграции}.Сообщение
```

Метод заменен на

[УстановитьПараметр](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

.

---

### УстановитьТелоИзПотока

`Доступность: Сервер`

```
УстановитьТелоИзПотока(Поток: ПотокЧтения): {ИмяПроцессаИнтеграции}.Сообщение
```

Переопределяет метод

[УстановитьТелоИзПотока](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

, возвращает сообщение конкретного, а не базового типа.

**Переопределение** [СообщениеИнтеграции::УстановитьТелоИзПотока](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

### УстановитьТелоИзСтроки

`Версия 9.0 и выше`

`Доступность: Сервер`

```
УстановитьТелоИзСтроки(
  Строка: Строка,
  Кодировка: Кодировка|Строка = Кодировка.Utf8
): {ИмяПроцессаИнтеграции}.Сообщение
```

**Переопределение** [СообщениеИнтеграции::УстановитьТелоИзСтроки](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

---

## Список унаследованных методов

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

### СообщениеИнтеграции

[Копировать](../../wiki/integration/integrationmessage-ru-379e89488b99.md) [(Переопределение)](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

[ПолучитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

[ПолучитьПараметрИлиУмолчание](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

[ПолучитьТелоКакПоток](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

[ПолучитьТелоКакСтроку](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

[СодержитПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md)

[УдалитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md) [(Переопределение)](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

[УстановитьКодыПолучателей](../../wiki/integration/integrationmessage-ru-379e89488b99.md) [(Переопределение)](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

[УстановитьПараметр](../../wiki/integration/integrationmessage-ru-379e89488b99.md) [(Переопределение)](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

[УстановитьТелоИзПотока](../../wiki/integration/integrationmessage-ru-379e89488b99.md) [(Переопределение)](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

[УстановитьТелоИзСтроки](../../wiki/integration/integrationmessage-ru-379e89488b99.md) [(Переопределение)](../../wiki/integration/integrationprocessname-message-ru-b27a7d9222f7.md)

## Список унаследованных свойств

### СообщениеИнтеграции

[Url](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [АбсолютныйПутьФайла](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ЗапросHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [Ид](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ИменаВсехПараметров](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ИмяФайла](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [КаталогФайла](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [КлючKafka](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [КлючМаршрутизацииRabbitMq](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [КодОтветаHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [КодировкаHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [КодыПолучателей](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [МетодHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ОтметкаВремениОтправкиKafka](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ОтносительныйПутьФайла](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [Параметры](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ПутьHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [РазделKafka](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [РазмерФайла](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [СмещениеKafka](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ТекстОтветаHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ТекстОшибкиБд](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ТипСодержимогоHttp](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ТопикKafka](../../wiki/integration/integrationmessage-ru-379e89488b99.md), [ФайлИзменен](../../wiki/integration/integrationmessage-ru-379e89488b99.md)
