# Элемент проекта вида «КонтрактСервиса»

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [service-contract-5b8423b5cca0-3dbfa6e6a0247398](../../raw/text-10.0/service-contract-5b8423b5cca0-3dbfa6e6a0247398.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Элемент проекта вида «КонтрактСервиса»`, `service-contract`.

## Обзор

Контракт сервиса предназначен для описания программного интерфейса, который можно реализовать в типах-одиночках.

## Документированный контракт и примеры

Контракт сервиса предназначен для описания программного интерфейса, который можно реализовать в типах-одиночках.

Контракт сервиса можно реализовать в следующих элементах проекта:

1. [Общий модуль](../language/common-module-4cc0343a9ddb.md)
  
  — методы в общем модуле, тип
  
  <ИмяОбщегоМодуля>
  
  .
2. [План обмена](../integration/exchange-plan-project-element-c0fc3c4bb4ef.md)
  
  — методы в
  
  [модуле плана обмена](../integration/exchange-plan-types-3ec789f3d859.md)
  
  , тип
  
  [<ИмяПланаОбмена>](../integration/exchange-plan-types-3ec789f3d859.md)
  
  .
3. [Интегрируемое приложение](integrable-application-project-element-9568214a365e.md)
  
  — методы в
  
  [модуле интегрируемого приложения](../language/integrable-application-types-11aeb893dc09.md)
  
  , тип
  
  [<ИмяИнтегрируемогоПриложения>](../language/integrable-application-types-11aeb893dc09.md)
  
  .
4. [Справочник](../data/catalog-project-element-b6ca52d114d4.md)
  
  — методы в
  
  [модуле справочника](../data/catalog-types-e0c7c64f0c49.md)
  
  , тип
  
  [<ИмяСправочника>](../data/catalog-types-e0c7c64f0c49.md)
  
  .
5. [Регистр сведений](../data/information-register-project-element-8932693c91b1.md)
  
  — методы в
  
  [модуле регистра сведений](../data/information-register-types-a915e7f32292.md)
  
  , тип
  
  [<ИмяРегистраСведений>](../data/information-register-types-a915e7f32292.md)
  
  .
6. [Регистр накопления](../data/accumulation-register-overview-699bd9df5dda.md)
  
  — методы в
  
  [модуле регистра накопления](../data/accumulation-register-types-222fcd7cfbd3.md)
  
  , тип
  
  [<ИмяРегистраНакопления>](../data/accumulation-register-types-222fcd7cfbd3.md)
  
  .
7. [Набор констант](constants-set-element-3c8e873b235a.md)
  
  — методы в
  
  [модуле набора констант](../language/constants-set-types-7dda7f31cc8d.md)
  
  , тип
  
  [<ИмяНабораКонстант>](../language/constants-set-types-7dda7f31cc8d.md)
  
  .
8. [Обычная команда](../language/usual-command-5d6bb6c02c99.md)
  
  — методы в
  
  [модуле обычной команды](../language/usual-command-5d6bb6c02c99.md)
  
  , тип
  
  [<ИмяОбычнойКоманды>](../language/usual-command-5d6bb6c02c99.md)
  
  .
9. [Переключаемая команда](../language/switchable-command-71037e8e27ae.md)
  
  — методы в
  
  [модуле переключаемой команды](../language/switchable-command-71037e8e27ae.md)
  
  , тип
  
  [<ИмяПереключаемойКоманды>](../language/switchable-command-71037e8e27ae.md)
  
  .

Модуль элемента-реализации должен содержать реализацию всех [методов контракта](../language/service-contract-type-ab46a6c6ee9c.md).

## Наследование контрактов сервиса

При [наследовании контрактов](contract-project-elements-4bb89cb1f89f.md) сервиса действуют следующие ограничения:

- Если базовый контракт
  
  [множественный](servicecontract-ru-c54f5cfcd100.md)
  
  , то наследник может быть одиночным и множественным.
- Если базовый контракт одиночный, то наследник может быть только одиночным.
- Признак
  
  [обязательности](servicecontract-ru-c54f5cfcd100.md)
  
  может быть любым, независимо от базового контракта.

## Примеры

- [Пример контракта сервиса](service-contract-example-c1e8b63cb74c.md)

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Элемент проекта вида «КонтрактСервиса»](https://1cmycloud.com/console/help/element/10.0/docs/topics/service-contract/).
