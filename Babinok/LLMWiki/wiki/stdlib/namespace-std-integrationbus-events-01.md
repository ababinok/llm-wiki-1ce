# Стд::ИнтеграционнаяШина::События

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [integrationprocessexecutionoperation-ru-1a618b997df9-7d994d7bed439540](../../raw/text-10.0/integrationprocessexecutionoperation-ru-1a618b997df9-7d994d7bed439540.md); [integrationprocessmessagevalidationerror-ru-6bc7d5ac3456-639b07e7178391c9](../../raw/text-10.0/integrationprocessmessagevalidationerror-ru-6bc7d5ac3456-639b07e7178391c9.md); [integrationprocessexecutionerror-ru-b60ff9230728-9d7a4f68e0fa5bec](../../raw/text-10.0/integrationprocessexecutionerror-ru-b60ff9230728-9d7a4f68e0fa5bec.md); [integrationprocessnodepropertycalculationerror-ru-64852aaac4df-7b3e5a5532308ba7](../../raw/text-10.0/integrationprocessnodepropertycalculationerror-ru-64852aaac4df-7b3e5a5532308ba7.md); [integrationprocessstarterror-ru-0c6bcd9e1b13-407911e6ea121f47](../../raw/text-10.0/integrationprocessstarterror-ru-0c6bcd9e1b13-407911e6ea121f47.md); [integrationprocessstoperror-ru-42f755f2a271-7f635861b9f83efe](../../raw/text-10.0/integrationprocessstoperror-ru-42f755f2a271-7f635861b9f83efe.md); [integrationprocesspermissionscheckerror-ru-da622e3d7555-867ad05f4ad0c3e0](../../raw/text-10.0/integrationprocesspermissionscheckerror-ru-da622e3d7555-867ad05f4ad0c3e0.md); [deliveredmessagesentevent-ru-381a87c3e8bb-417b3f59d47647ac](../../raw/text-10.0/deliveredmessagesentevent-ru-381a87c3e8bb-417b3f59d47647ac.md); [undeliveredmessagesentevent-ru-de75a337f804-8e2cf850997f6c01](../../raw/text-10.0/undeliveredmessagesentevent-ru-de75a337f804-8e2cf850997f6c01.md); [integrationprocessparameterchangedevent-ru-bd7472ad0841-1c797423fc1fb441](../../raw/text-10.0/integrationprocessparameterchangedevent-ru-bd7472ad0841-1c797423fc1fb441.md); [integrationprocessstartedevent-ru-abb1686affb3-a98acff89a793e48](../../raw/text-10.0/integrationprocessstartedevent-ru-abb1686affb3-a98acff89a793e48.md); [integrationprocessstoppedevent-ru-5b1f1d2c4411-00308933b512a665](../../raw/text-10.0/integrationprocessstoppedevent-ru-5b1f1d2c4411-00308933b512a665.md); [integrationprocessmessagedeliveredevent-ru-fecf06232736-3859eb1f502525cb](../../raw/text-10.0/integrationprocessmessagedeliveredevent-ru-fecf06232736-3859eb1f502525cb.md); [events-0eccf43873da-e41ef84dfc6ea272](../../raw/text-10.0/events-0eccf43873da-e41ef84dfc6ea272.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Пространства имён](namespaces.md)

- [ОперацияВыполнениеПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessexecutionoperation-ru-1a618b997df9.md)
- [ОшибкаВалидацииСообщенияПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessmessagevalidationerror-ru-6bc7d5ac3456.md)
- [ОшибкаВыполненияПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessexecutionerror-ru-b60ff9230728.md)
- [ОшибкаВычисленияСвойстваУзлаПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessnodepropertycalculationerror-ru-64852aaac4df.md)
- [ОшибкаЗапускаПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessstarterror-ru-0c6bcd9e1b13.md)
- [ОшибкаОстановкиПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessstoperror-ru-42f755f2a271.md)
- [ОшибкаПроверкиРазрешенийПроцессаИнтеграции — Программный тип XBSL: Std / IntegrationBus / Events](../security/integrationprocesspermissionscheckerror-ru-da622e3d7555.md)
- [СобытиеДоставленноеСообщениеОтправлено — Программный тип XBSL: Std / IntegrationBus / Events](../integration/deliveredmessagesentevent-ru-381a87c3e8bb.md)
- [СобытиеНедоставленноеСообщениеОтправлено — Программный тип XBSL: Std / IntegrationBus / Events](../integration/undeliveredmessagesentevent-ru-de75a337f804.md)
- [СобытиеПараметрПроцессаИнтеграцииИзменен — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessparameterchangedevent-ru-bd7472ad0841.md)
- [СобытиеПроцессИнтеграцииЗапущен — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessstartedevent-ru-abb1686affb3.md)
- [СобытиеПроцессИнтеграцииОстановлен — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessstoppedevent-ru-5b1f1d2c4411.md)
- [СобытиеСообщениеПроцессаИнтеграцииДоставлено — Программный тип XBSL: Std / IntegrationBus / Events](../integration/integrationprocessmessagedeliveredevent-ru-fecf06232736.md)
- [Стд::ИнтеграционнаяШина::События — Пространство имён XBSL: Std / IntegrationBus](../integration/events-0eccf43873da.md)
