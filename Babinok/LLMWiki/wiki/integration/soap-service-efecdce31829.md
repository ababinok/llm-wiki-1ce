# Элемент проекта вида «SoapСервис»

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [soap-service-efecdce31829-23ed5968ca62eb91](../../raw/text-10.0/soap-service-efecdce31829-23ed5968ca62eb91.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Элемент проекта вида «SoapСервис»`, `soap-service`.

## Обзор

Для создания SOAP-сервиса следует добавить в проект элемент **SOAP-сервис**.

## Документированный контракт и примеры

Для создания SOAP-сервиса следует добавить в проект элемент **SOAP-сервис**.

В описании элемента проекта указываются настройки создаваемого сервиса, его свойства и методы, которые реализуют операции SOAP-сервиса. Модуль SOAP-сервиса содержит описание передаваемых данных (структур языка «1С:Элемент»), пользовательских исключений, а также реализацию операций сервиса.

## Описание элемента проекта «SoapСервис»

При создании описания SOAP-сервиса вам необходимо определить следующие свойства:

1. ПространствоИменСервиса
  
  — пространство имен, в котором описан сервис. Атрибут
  
  `targetNamespace`
  
  WSDL-описания сервиса (
  
  `definitions.targetNamespace`
  
  ).
2. ИмяСервиса
  
  — имя сервиса. Атрибут
  
  `name`
  
  WSDL-описания сервиса (
  
  `definitions.name`
  
  ). Если не указан, то используется имя элемента проекта.
3. КорневойUrl
  
  — базовая часть URL, по которой будет выполняться обращение к сервису.
4. Обработчики
  
  — описание операций, которые выполняют обработку данных из входящего SOAP-сообщения от клиента сервиса и формируют результат для исходящего SOAP-сообщения. Для каждой операции вы должны создать метод, который реализует необходимую функциональность. Методы находятся в модуле SOAP-сервиса.

Например, SOAP-сервис может выглядеть следующим образом:

```yaml
ВидЭлемента: SoapСервис
ОбластьВидимости: ВПроекте
Ид: 20658364-7777-4b14-9423-ec212de5be72
Имя: СервисМагазина
ИмяСервиса: ShopService
КорневойUrl: shopservice
ПространствоИменСервиса: https://mycustomshop.ru
КонтрольДоступа:
    Разрешения:
        Вызов: РазрешенияВычисляются
        ПоУмолчанию: РазрешенияВычисляются
Обработчики:
    -
        Имя: AddToCart
        Метод: ДобавитьВКорзину
        КонтрольДоступа:
            Обработчик: ВычислитьРазрешенияДляОперации
            Разрешения:
                Вызов: РазрешенияВычисляются
```

## Модуль SOAP-сервиса

В модуле SOAP-сервиса следует добавить:

1. Структуры, которые описывают передаваемые в сервис параметры и результат запроса. Вместо структур можно также использовать встроенные типы —
  
  `Число`
  
  ,
  
  `Строка`
  
  и т. д. Данные типы будут автоматически сопоставлены с соответствующими XML-типами.
2. Используемые в сервисе исключения. Данные типы будут сопоставлены с SOAP-ошибками.
3. Методы для описания операций, выполняемых в результате вызова обработчиков.

Пример модуля SOAP-сервиса:

```xbsl
// Описание пользовательской ошибки
@ВПроекте
исключение ShopServiceException
  обз пер ErrorDescription: Строка
  обз пер ErrorCode: Число
;

// Структура, описывающая параметры обработчика
структура Item
    обз пер Id: Число
    обз пер Name: Строка
    обз пер Price: Число
;

// Обработчик операции сервиса
метод ДобавитьВКорзину(Товар: Item, Количество: Число)
    // Метод, написанный разработчиком
;
```

### Ограничения на код модуля

1. Запрещено использовать кириллицу в именах обработчиков.
2. В структурах языка «1С:Элемент», используемых в сообщениях (параметрах и возвращаемых значениях обработчиков SOAP-сервиса), в заголовках, а также исключениях, используемых как SOAP-ошибки:
  
  - Не должно быть циклических ссылок.
  - Допустим только составной тип, состоящий из одного из поддерживаемых типов +
    
    `Неопределено`
    
    . В этом случае в XML-элементе будет использовано ограничение
    
    `minOccurs=0`
    
    . Другие составные типы не разрешены.
  - Допустимы только следующие типы данных:
  
  | Тип | XML тип | Примечание |
  | --- | --- | --- |
  | `Строка` | `string` |  |
  | `Число` | `decimal` |  |
  | `Булево` | `boolean` |  |
  | `ДатаВремя` | `dateTime` |  |
  | `Дата` | `date` |  |
  | `Время` | `time` |  |
  | `Месяц` | `gMonth` |  |
  | `Длительность` | `duration` |  |
  | `Байты` | `base64Binary` |  |
  | `Структура` |  | `complexType` |
  | `Неопределено` |  | `minOccurs=0` |
  | `ЧитаемаяКоллекция<Тип>`, где `Тип` — значения поддерживаемого типа |  | `minOccurs=unbounded`; не поддерживается коллекция коллекций |

Также в модуле SOAP-сервиса можно обработать событие `ВычислитьРазрешенияДоступа` ([подробнее](../security/manage-access-control-2ec0764ce511.md)).

## WSDL-описание SOAP-сервиса

«1С:Предприятие.Элемент» из элемента проекта формирует WSDL-описание SOAP-сервиса. Чтобы получить описание, следует выполнить GET-запрос к сервису с параметром `?wsdl`. Пример:

```xml
<definitions xmlns="http://schemas.xmlsoap.org/wsdl/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:tns="https://mycustomshop.ru" xmlns:soap="http://schemas.xmlsoap.org/wsdl/soap/" targetNamespace="https://mycustomshop.ru">
    <types>
        <xsd:schema>
            <xsd:import namespace="https://mycustomshop.ru" schemaLocation="http://127.0.0.1:9090/applications/soap-service-app/api/shopservice?xsd=1"/>
        </xsd:schema>
    </types>
    <message name="AddToCart">
        <part name="parameters" element="tns:AddToCart"/>
    </message>
    <message name="AddToCartResponse">
        <part name="parameters" element="tns:AddToCartResponse"/>
    </message>
    <message name="ShopServiceException">
        <part name="fault" element="tns:ShopServiceException"/>
    </message>
    <portType name="ShopService">
        <operation name="AddToCart">
            <input message="tns:AddToCart"/>
            <output message="tns:AddToCartResponse"/>
            <fault message="tns:ShopServiceException" name="ShopServiceException"/>
        </operation>
    </portType>
    <binding name="ShopServicePortBinding" type="tns:ShopService">
        <soap:binding transport="http://schemas.xmlsoap.org/soap/http" style="document"/>
        <operation name="AddToCart">
            <soap:operation soapAction="AddToCart"/>
            <input>
                <soap:body use="literal"/>
            </input>
            <output>
                <soap:body use="literal"/>
            </output>
            <fault name="ShopServiceException">
                <soap:fault name="ShopServiceException" use="literal"/>
            </fault>
        </operation>
    </binding>
    <service name="ShopService">
        <port name="ShopServicePort" binding="tns:ShopServicePortBinding">
            <soap:address location="http://127.0.0.1:9090/applications/soap-service-app/api/shopservice"/>
        </port>
    </service>
</definitions>
```

## URL для запроса к SOAP-сервису

Сервис обрабатывает POST-запросы. Корректный URL запроса к SOAP-сервису должен иметь следующую структуру:

```text
{АдресПубликацииПриложения}/api/{КорневойURL}
```

Для данного элемента проекта приложение будет обрабатывать SOAP-запросы к сервису по пути:

```text
http://[адрес сервера]/applications/[имя приложения]/api/shopservice
```

Чтобы получить WSDL-описание сервиса, следует отправить GET-запрос с параметром *?wsdl*. Например:

```text
http://[адрес сервера]/applications/[имя приложения]/api/shopservice?wsdl
```

Рассмотрим части запроса по порядку:

- http или https: `http://`
  
  Используемый протокол.
- АдресПубликацииПриложения: `[адрес сервера]/applications/[имя приложения]/`
  
  Адрес «1С:Предприятие.Элемента» и путь публикации приложения на сервере.
- api: `api/`
  
  Признак того, что данный URL представляет запрос к публичному API приложения.
- КорневойURL: `shopservice`
  
  Относительный URL сервиса. Должен быть уникальным среди всех сервисов в проекте. Определяет конкретный сервис, который должен обработать запрос.
- ПараметрыЗапроса: `?wsdl`
  
  Стандартный способ передачи параметров запроса через URL.

## Права

Элемент проекта вида **SoapСервис** обладает правом **Вызов** ([подробнее](../security/project-element-permissions-12c1d76e1615.md)).

Событие `ВычислитьРазрешенияДоступа` следует [обрабатывать](../security/manage-access-control-2ec0764ce511.md) в [модуле SOAP-сервиса](soap-service-types-a958b90025c0.md).

## См. также

- [Свойства SOAP-сервиса](soapservice-33331940c1db.md)

## See Also

- [Навигатор раздела](overview.md)
- [HTTP-клиент и обработка JSON](http-and-json.md)
- [Процессы интеграции и ограничения облака](integration-processes-and-cloud.md)
- [Маршрут: HTTP-ответ, JSON и обработка ошибок](http-json-response-route.md)

Оригинал: [Элемент проекта вида «SoapСервис»](https://1cmycloud.com/console/help/element/10.0/docs/topics/soap-service/).
