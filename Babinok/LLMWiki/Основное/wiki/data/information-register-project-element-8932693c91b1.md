# Элемент проекта вида «РегистрСведений»

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [information-register-project-element-8932693c91b1-c99ced82cebe5efb](../../raw/text-10.0/information-register-project-element-8932693c91b1-c99ced82cebe5efb.md); [ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1](../../raw/figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Элемент проекта вида «РегистрСведений»`, `information-register-project-element`.

## Обзор

Данные, хранящиеся в регистре сведений, можно представить в виде таблицы, имеющей одну или несколько колонок.

## Документированный контракт и примеры

Данные, хранящиеся в регистре сведений, можно представить в виде таблицы, имеющей одну или несколько колонок. По своему назначению колонки делятся на три группы:

- Измерения
  
  — это «координаты» или значения, для которых в регистре хранится некоторая информация. Например, в регистре
  
  Цены товаров для покупателей
  
  измерениями будут товар и покупатель, для которого данный товар имеет некоторую цену;
- Ресурсы
  
  — это основная информация, хранимая в регистре. Например, в том же регистре это будет цена товара;
- Реквизиты
  
  — это вспомогательная информация, которая относится только к одной строке таблицы. Например, фамилия менеджера, который установил данную цену.

| Измерение: Покупатель | Измерение: Товар | Ресурс: Цена | Реквизит: ФИО |
| --- | --- | --- | --- |
| Магазин «Луч» | Монитор | 14 000 | Булатов И.В. |
| Предприятие «Ротор» | Монитор | 11 000 | Орлова Е.Н. |
| Магазин «Луч» | Принтер | 10 000 | Булатов И.В. |
| Предприятие «Ротор» | Мышь | 2 000 | Громова Н.П. |

Строки этой таблицы являются записями регистра:

- для магазина «Луч» монитор стоит 14 000 (эту цену установил Булатов);
- для предприятия «Ротор» этот же монитор стоит 11 000 (эту цену установила Орлова);
- для магазина «Луч» принтер стоит 10 000 (эту цену установил Булатов) и т. д.

Чтобы создать такую структуру данных в приложении, добавьте в проект элемент вида **РегистрСведений**. Он будет описывать состав колонок такой таблицы и другие свойства, которые необходимы для работы с этими данными.

Вид **РегистрСведений** содержит специальные свойства, которые соответствуют колонкам таблицы: **измерения**, **ресурсы** и **реквизиты**. В проекте вы можете добавить регистру сведений одно или несколько измерений, а также необходимое вам количество ресурсов и реквизитов.

> [!TIP] совет
> Измерения, ресурсы и реквизиты регистра сведений могут реализовывать [контракт типа](../language/type-contract-ab9f0932850d.md).

Чаще всего регистр сведений имеет несколько измерений и несколько ресурсов. В самом простом случае регистр может иметь только одно измерение, ресурс или реквизит.

## Независимый и подчиненный регистры сведений

С помощью свойства [РежимЗаписи](informationregister-10bb0480b19f.md) вы можете определить режим записи регистра:

- Независимый
  
  (по умолчанию) — используется для хранения сведений, не требующих подтверждения документами.
- [ПодчинениеРегистратору](subordinated-information-register-7e7da053300b.md)
  
  — запись сведений в регистр выполняется с обязательным указанием подтверждающего документа-регистратора.

## Права

Элемент проекта вида **РегистрСведений** обладает следующими правами: **Чтение** и **Изменение** ([подробнее](../security/project-element-permissions-12c1d76e1615.md)).

События `ВычислитьРазрешенияДоступа`, `ВычислитьРазрешенияДоступаДляОбъектов` ([подробнее](../security/manage-access-control-2ec0764ce511.md)), `ВычислитьКлючиДоступаДляЧтения` и `ВычислитьКлючиДоступаДляИзменения` ([подробнее](rights-for-information-registers-20135b8da0f0.md)) следует обрабатывать в [модуле регистра сведений](information-register-types-a915e7f32292.md).

## См. также

- [Запись данных в оптимизированном режиме](../language/group-operations-6d6c6a6c6ef5.md)
- [Таблицы языка запросов](../queries/informationregistername-ru-681ea4b3be13.md)
- [Таблица регистрации изменений](../queries/documentname-changes-ru-8870f3a4ed1b.md)
- [Подчиненный регистр сведений](subordinated-information-register-7e7da053300b.md)


Совет. [Описание иллюстрации](../../raw/figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md)

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяРегистраСведений}.АвтоматическаяФормаСписка.Контекст — Порождаемый тип XBSL: InformationRegisterName](informationregistername-automaticlistform-context-ru-b36948bffcf3.md)
- [{ИмяРегистраСведений}.АвтоматическаяФормаСписка — Порождаемый тип XBSL: InformationRegisterName](informationregistername-automaticlistform-ru-af7d435a292f.md)
- [{ИмяРегистраСведений}.АвтоматическаяФормаЗаписи.Контекст — Порождаемый тип XBSL: InformationRegisterName](informationregistername-automaticrecordform-context-ru-aa70964fa2f7.md)
- [{ИмяРегистраСведений}.АвтоматическаяФормаЗаписи — Порождаемый тип XBSL: InformationRegisterName](informationregistername-automaticrecordform-ru-d627c6735e73.md)
- [{ИмяРегистраСведений}.СоздатьОбъект — Порождаемый тип XBSL: InformationRegisterName](informationregistername-createobject-ru-3bd63e8333f5.md)
- [{ИмяРегистраСведений}.Данные — Порождаемый тип XBSL: InformationRegisterName](informationregistername-data-ru-51d1bfdf0487.md)
- [{ИмяРегистраСведений}.КлючРазрешенийИзмерений — Порождаемый тип XBSL: InformationRegisterName](../security/informationregistername-dimensionspermissionskey-ru-5e3793f55f4e.md)
- [{ИмяРегистраСведений}.Блокировки.Измерения — Порождаемый тип XBSL: InformationRegisterName](informationregistername-locks-dimensions-ru-18c2724f5403.md)
- [{ИмяРегистраСведений}.Блокировки.КлючЗаписи — Порождаемый тип XBSL: InformationRegisterName](informationregistername-locks-recordkey-ru-b51492eba1cb.md)
- [{ИмяРегистраСведений}.КлючОсновногоФильтра — Порождаемый тип XBSL: InformationRegisterName](informationregistername-mainfilterkey-ru-b2b91a95f0cf.md)
- [{ИмяРегистраСведений}.ОткрытьСписок — Порождаемый тип XBSL: InformationRegisterName](informationregistername-openlist-ru-d5af0d432ae6.md)
- [{ИмяРегистраСведений}.ДанныеРасчетаРазрешений — Порождаемый тип XBSL: InformationRegisterName](../security/informationregistername-permissionscomputedata-ru-f3d9fac0de71.md)
- [{ИмяРегистраСведений}.КлючЗаписи — Порождаемый тип XBSL: InformationRegisterName](informationregistername-recordkey-ru-2cfab865dace.md)
- [{ИмяРегистраСведений}.НаборЗаписей.Данные — Порождаемый тип XBSL: InformationRegisterName](informationregistername-recordset-data-ru-7d58b014161b.md)
- [{ИмяРегистраСведений}.НаборЗаписей.Фильтр.Данные — Порождаемый тип XBSL: InformationRegisterName](informationregistername-recordset-filter-data-ru-ff8619597803.md)
- [{ИмяРегистраСведений}.НаборЗаписей.Фильтр — Порождаемый тип XBSL: InformationRegisterName](informationregistername-recordset-filter-ru-946995f1b815.md)
- [{ИмяРегистраСведений}.НаборЗаписей — Порождаемый тип XBSL: InformationRegisterName](informationregistername-recordset-ru-ff0cb8e8f1d1.md)
- [{ИмяРегистраСведений}.Запись — Порождаемый тип XBSL: InformationRegisterName](informationregistername-record-ru-2194321bf71d.md)
- [{ИмяРегистраСведений}.ПараметрыЗаписи — Порождаемый тип XBSL: InformationRegisterName](informationregistername-writeparameters-ru-2c1311693cd8.md)
- [{ИмяРегистраСведений} — Порождаемый тип XBSL: InformationRegisterName](informationregistername-ru-a758d6e52059.md)
- [РегистрСведений — Элемент проекта](informationregister-10bb0480b19f.md)
- [Хранимые данные и порождаемые типы](entities-and-generated-types.md)
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md)

Оригинал: [Элемент проекта вида «РегистрСведений»](https://1cmycloud.com/console/help/element/10.0/docs/topics/information-register-project-element/).
