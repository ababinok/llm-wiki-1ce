# Данные и хранение

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [catalog-project-element-b6ca52d114d4-05a6ee60331e001e](../../raw/text-10.0/catalog-project-element-b6ca52d114d4-05a6ee60331e001e.md); [catalog-types-e0c7c64f0c49-c147cf951d586e7f](../../raw/text-10.0/catalog-types-e0c7c64f0c49-c147cf951d586e7f.md); [information-register-project-element-8932693c91b1-c99ced82cebe5efb](../../raw/text-10.0/information-register-project-element-8932693c91b1-c99ced82cebe5efb.md); [information-register-types-a915e7f32292-9712d4fe3e6872bb](../../raw/text-10.0/information-register-types-a915e7f32292-9712d4fe3e6872bb.md); [object-form-component-98dd1d49f7f9-136bb0725006925a](../../raw/text-10.0/object-form-component-98dd1d49f7f9-136bb0725006925a.md); [edit-object-form-38639ef4b408-07eb2c446b2513d2](../../raw/text-10.0/edit-object-form-38639ef4b408-07eb2c446b2513d2.md); [catalogname-reference-ru-27f8093271c9-7ea93bcaac83802b](../../raw/text-10.0/catalogname-reference-ru-27f8093271c9-7ea93bcaac83802b.md); [catalogname-object-ru-8fd7b105e091-ab305f6a03be4ea6](../../raw/text-10.0/catalogname-object-ru-8fd7b105e091-ab305f6a03be4ea6.md); [autonumber-elements-b3820bf0ba6d-a2a5fd1b42b7c978](../../raw/text-10.0/autonumber-elements-b3820bf0ba6d-a2a5fd1b42b7c978.md); [accumulationregisterrecordkind-ru-96dc52c05b6c-f2bab24d4620a735](../../raw/text-10.0/accumulationregisterrecordkind-ru-96dc52c05b6c-f2bab24d4620a735.md); [catalog-ru-2804b6898555-ca32c53a67ff4b9e](../../raw/text-10.0/catalog-ru-2804b6898555-ca32c53a67ff4b9e.md); [cataloghierarchykind-ru-73abb2961f03-55d5a1a73a9b216b](../../raw/text-10.0/cataloghierarchykind-ru-73abb2961f03-55d5a1a73a9b216b.md); [constantsset-ru-8ee9270478c2-cc9202cc3c88b1f7](../../raw/text-10.0/constantsset-ru-8ee9270478c2-cc9202cc3c88b1f7.md); [null-ru-0059ad0ae7ba-d21899fd5728afb6](../../raw/text-10.0/null-ru-0059ad0ae7ba-d21899fd5728afb6.md); [transactionrollbackevent-ru-4b815f2b556e-d1126f7b14c48d68](../../raw/text-10.0/transactionrollbackevent-ru-4b815f2b556e-d1126f7b14c48d68.md); [sqlquery-ru-81232e8a7d08-9b91c371269db6d5](../../raw/text-10.0/sqlquery-ru-81232e8a7d08-9b91c371269db6d5.md); [datareadexception-ru-8323ffdb9fa5-02a517e9d2c45c26](../../raw/text-10.0/datareadexception-ru-8323ffdb9fa5-02a517e9d2c45c26.md); [document-ru-b49d262f4dba-9dad073b6511a6f2](../../raw/text-10.0/document-ru-b49d262f4dba-9dad073b6511a6f2.md); [externalnavigationlinkkind-ru-5eecd0666842-e34e4e3ff3b93343](../../raw/text-10.0/externalnavigationlinkkind-ru-5eecd0666842-e34e4e3ff3b93343.md); [hierarchyownersmismatchexception-ru-0887bade9def-af8044faf3d36945](../../raw/text-10.0/hierarchyownersmismatchexception-ru-0887bade9def-af8044faf3d36945.md); [datalock-ru-b2f593db7ee9-369d326b98b8c799](../../raw/text-10.0/datalock-ru-b2f593db7ee9-369d326b98b8c799.md); [informationregister-ru-d15b0965bc15-7ed7d5cbfd9ff20e](../../raw/text-10.0/informationregister-ru-d15b0965bc15-7ed7d5cbfd9ff20e.md); [binaryobject-ru-a65f10db6bb3-7e072a1cc60dfe78](../../raw/text-10.0/binaryobject-ru-a65f10db6bb3-7e072a1cc60dfe78.md); [standardsettingsstorage-ru-45df1deaf228-7a37562fa2641a63](../../raw/text-10.0/standardsettingsstorage-ru-45df1deaf228-7a37562fa2641a63.md); [documentname-ru-a385526b4a75-0058a8aeab8f4745](../../raw/text-10.0/documentname-ru-a385526b4a75-0058a8aeab8f4745.md); [settingsstoragename-locks-reference-ru-068bc739ef33-3e83ec22bf5d3292](../../raw/text-10.0/settingsstoragename-locks-reference-ru-068bc739ef33-3e83ec22bf5d3292.md); [database-c7a95b8f6198-8d72ca88561f77c4](../../raw/text-10.0/database-c7a95b8f6198-8d72ca88561f77c4.md); [accumulation-register-0d40727223d8-5b759e6ebd127936](../../raw/text-10.0/accumulation-register-0d40727223d8-5b759e6ebd127936.md); [owner-ru-5eab6bf42cc6-088cf9af94c84ac7](../../raw/text-10.0/owner-ru-5eab6bf42cc6-088cf9af94c84ac7.md)
> Updated: 2026-10-05

Версия: `10.0`.

## Тематические объяснения

- [Хранимые данные и порождаемые типы](entities-and-generated-types.md) — Справочники, регистры и различия ссылок, объектов и данных.
- [Маршрут: форма объекта и операции со справочником](object-form-and-crud.md) — Форма, ссылка и объект: создание, загрузка, запись и удаление с учётом окружения.

## Оглавление справочника

Счётчики рассчитаны по реестру покрытия. Точные источники каждого описания находятся в соответствующем групповом индексе.

| Группа | Статей |
| --- | ---: |
| [Руководство разработчика](index-guide-01.md) | 49 |
| [XBSL: Std::AccumulationRegisters](index-xbsl-accumulationregisters-01.md) | 10 |
| [XBSL: Std::Catalogs](index-xbsl-catalogs-01.md) | 4 |
| [XBSL: Std::Catalogs::Reflection](index-xbsl-catalogs-reflection-01.md) | 3 |
| [XBSL: Std::ConstantsSets](index-xbsl-constantssets-01.md) | 5 |
| [XBSL: Std::Database](index-xbsl-database-01.md) | 23 |
| [XBSL: Std::Database::Events](index-xbsl-database-events-01.md) | 2 |
| [XBSL: Std::Database::Sql](index-xbsl-database-sql-01.md) | 10 |
| [XBSL: Std::DataSchema](index-xbsl-dataschema-01.md) | 1 |
| [XBSL: Std::Documents](index-xbsl-documents-01.md) | 4 |
| [XBSL: Std::Entities](index-xbsl-entities-01.md) | 32 |
| [XBSL: Std::Entities::Hierarchy](index-xbsl-entities-hierarchy-01.md) | 2 |
| [XBSL: Std::Entities::Locks](index-xbsl-entities-locks-01.md) | 6 |
| [XBSL: Std::InformationRegisters](index-xbsl-informationregisters-01.md) | 7 |
| [XBSL: Std::ObjectStorage](index-xbsl-objectstorage-01.md) | 12 |
| [XBSL: Std::SettingsStorages](index-xbsl-settingsstorages-01.md) | 14 |
| [Прикладные и генерируемые типы XBSL — часть 1: {ИмяДокумента} … {ИмяХранилищаНастроек}.АвтоматическаяФормаСписка.Контекст](index-generated-01.md) | 100 |
| [Прикладные и генерируемые типы XBSL — часть 2: {ИмяХранилищаНастроек}.Блокировки.Ссылка … {ИмяХранимойСтруктуры}.Данные](index-generated-02.md) | 10 |
| [Пространства имён XBSL](index-namespaces-01.md) | 15 |
| [Термины](index-glossary-01.md) | 6 |
| [Элементы проекта](index-elements-01.md) | 64 |

## See Also

- [Общий индекс](../index.md)
- [Пространства имён](../stdlib/namespaces.md)
- [Компоненты: руководство и контракты](../interface/component-map.md)
- [Элементы проекта и порождаемые типы](../project/element-map.md)
