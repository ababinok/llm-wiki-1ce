# Элемент проекта вида «КонтрактСервиса»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/service-contract/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/service-contract/index.html
> SHA256: b05f7275f833ddf6b73c9ba6569843be6ee1591dec7f00cfaf32e5fc9c4ca50e
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Контракт сервиса предназначен для описания программного интерфейса, который можно реализовать в типах-одиночках.

Контракт сервиса можно реализовать в следующих элементах проекта:

1. [Общий модуль](../../wiki/language/common-module-4cc0343a9ddb.md)
  
  — методы в общем модуле, тип
  
  <ИмяОбщегоМодуля>
  
  .
2. [План обмена](../../wiki/integration/exchange-plan-project-element-c0fc3c4bb4ef.md)
  
  — методы в
  
  [модуле плана обмена](../../wiki/integration/exchange-plan-types-3ec789f3d859.md)
  
  , тип
  
  [<ИмяПланаОбмена>](../../wiki/integration/exchange-plan-types-3ec789f3d859.md)
  
  .
3. [Интегрируемое приложение](../../wiki/project/integrable-application-project-element-9568214a365e.md)
  
  — методы в
  
  [модуле интегрируемого приложения](../../wiki/language/integrable-application-types-11aeb893dc09.md)
  
  , тип
  
  [<ИмяИнтегрируемогоПриложения>](../../wiki/language/integrable-application-types-11aeb893dc09.md)
  
  .
4. [Справочник](../../wiki/data/catalog-project-element-b6ca52d114d4.md)
  
  — методы в
  
  [модуле справочника](../../wiki/data/catalog-types-e0c7c64f0c49.md)
  
  , тип
  
  [<ИмяСправочника>](../../wiki/data/catalog-types-e0c7c64f0c49.md)
  
  .
5. [Регистр сведений](../../wiki/data/information-register-project-element-8932693c91b1.md)
  
  — методы в
  
  [модуле регистра сведений](../../wiki/data/information-register-types-a915e7f32292.md)
  
  , тип
  
  [<ИмяРегистраСведений>](../../wiki/data/information-register-types-a915e7f32292.md)
  
  .
6. [Регистр накопления](../../wiki/data/accumulation-register-overview-699bd9df5dda.md)
  
  — методы в
  
  [модуле регистра накопления](../../wiki/data/accumulation-register-types-222fcd7cfbd3.md)
  
  , тип
  
  [<ИмяРегистраНакопления>](../../wiki/data/accumulation-register-types-222fcd7cfbd3.md)
  
  .
7. [Набор констант](../../wiki/project/constants-set-element-3c8e873b235a.md)
  
  — методы в
  
  [модуле набора констант](../../wiki/language/constants-set-types-7dda7f31cc8d.md)
  
  , тип
  
  [<ИмяНабораКонстант>](../../wiki/language/constants-set-types-7dda7f31cc8d.md)
  
  .
8. [Обычная команда](../../wiki/language/usual-command-5d6bb6c02c99.md)
  
  — методы в
  
  [модуле обычной команды](../../wiki/language/usual-command-5d6bb6c02c99.md)
  
  , тип
  
  [<ИмяОбычнойКоманды>](../../wiki/language/usual-command-5d6bb6c02c99.md)
  
  .
9. [Переключаемая команда](../../wiki/language/switchable-command-71037e8e27ae.md)
  
  — методы в
  
  [модуле переключаемой команды](../../wiki/language/switchable-command-71037e8e27ae.md)
  
  , тип
  
  [<ИмяПереключаемойКоманды>](../../wiki/language/switchable-command-71037e8e27ae.md)
  
  .

Модуль элемента-реализации должен содержать реализацию всех [методов контракта](../../wiki/language/service-contract-type-ab46a6c6ee9c.md).

## Наследование контрактов сервиса

При [наследовании контрактов](../../wiki/project/contract-project-elements-4bb89cb1f89f.md) сервиса действуют следующие ограничения:

- Если базовый контракт
  
  [множественный](../../wiki/project/servicecontract-ru-c54f5cfcd100.md)
  
  , то наследник может быть одиночным и множественным.
- Если базовый контракт одиночный, то наследник может быть только одиночным.
- Признак
  
  [обязательности](../../wiki/project/servicecontract-ru-c54f5cfcd100.md)
  
  может быть любым, независимо от базового контракта.

## Примеры

- [Пример контракта сервиса](../../wiki/project/service-contract-example-c1e8b63cb74c.md)
