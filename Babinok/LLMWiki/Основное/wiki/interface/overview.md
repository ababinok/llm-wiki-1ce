# Компоненты и поведение интерфейса

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [system-and-interface-components-18287074edda-e0278cb2e6ad00a1](../../raw/text-10.0/system-and-interface-components-18287074edda-e0278cb2e6ad00a1.md); [interface-component-types-b9d0cf747ffb-5ff3f050967702c2](../../raw/text-10.0/interface-component-types-b9d0cf747ffb-5ff3f050967702c2.md); [add-user-interface-component-dc23d126a446-5e0dfc5d0962d78a](../../raw/text-10.0/add-user-interface-component-dc23d126a446-5e0dfc5d0962d78a.md); [component-example-077c0c8b7fb0-c7af3a59d2022ca8](../../raw/text-10.0/component-example-077c0c8b7fb0-c7af3a59d2022ca8.md); [group-component-982f449c1db4-3f2c2c0d8ff0fa33](../../raw/text-10.0/group-component-982f449c1db4-3f2c2c0d8ff0fa33.md); [edit-component-a54ad83ade7f-f1b8eb34134e93d1](../../raw/text-10.0/edit-component-a54ad83ade7f-f1b8eb34134e93d1.md); [button-component-9e3a091652f8-e0aaa0f2bd089cc0](../../raw/text-10.0/button-component-9e3a091652f8-e0aaa0f2bd089cc0.md); [standard-list-component-e16dfcbb2f50-1cead47ef9204fe7](../../raw/text-10.0/standard-list-component-e16dfcbb2f50-1cead47ef9204fe7.md); [calculated-property-values-for-ui-components-05bce1d1d5e7-fcedf4f496e7f075](../../raw/text-10.0/calculated-property-values-for-ui-components-05bce1d1d5e7-fcedf4f496e7f075.md); [move-execution-from-client-to-server-7c6a7eed7a44-890b3beb63f6ecdd](../../raw/text-10.0/move-execution-from-client-to-server-7c6a7eed7a44-890b3beb63f6ecdd.md); [dynamic-list-560b781f9b9f-9a04d7292c66032e](../../raw/text-10.0/dynamic-list-560b781f9b9f-9a04d7292c66032e.md); [table-ru-ae448df56dfd-cc88dd68343c4638](../../raw/text-10.0/table-ru-ae448df56dfd-cc88dd68343c4638.md); [table-ru-ccc43dec1ca9-1cc38ef39de7e685](../../raw/text-10.0/table-ru-ccc43dec1ca9-1cc38ef39de7e685.md); [dynamiclist-ru-ab61b0be4de4-7de09a783e63e8a9](../../raw/text-10.0/dynamiclist-ru-ab61b0be4de4-7de09a783e63e8a9.md); [automatic-form-5b558ac26375-cdb84026335f82df](../../raw/text-10.0/automatic-form-5b558ac26375-cdb84026335f82df.md); [geographicroutekind-ru-8815af850ad3-5b410ed04770a8f1](../../raw/text-10.0/geographicroutekind-ru-8815af850ad3-5b410ed04770a8f1.md); [geographicmap-ru-f304d5897f94-800ce2813b7ff78a](../../raw/text-10.0/geographicmap-ru-f304d5897f94-800ce2813b7ff78a.md); [clientnotificationimportance-ru-0f8e8ec7170c-eaf747a2e7b8e60d](../../raw/text-10.0/clientnotificationimportance-ru-0f8e8ec7170c-eaf747a2e7b8e60d.md); [xychart-ru-e0769f4ee02b-8ef0a78926f92bac](../../raw/text-10.0/xychart-ru-e0769f4ee02b-8ef0a78926f92bac.md); [webchat-ru-3827b4bdb969-8b257d237d7eae40](../../raw/text-10.0/webchat-ru-3827b4bdb969-8b257d237d7eae40.md); [clipboard-ru-fb53761811e5-23fd435d2e2d4c95](../../raw/text-10.0/clipboard-ru-fb53761811e5-23fd435d2e2d4c95.md); [commandimportance-ru-986d64839edb-b052cb1f3abba688](../../raw/text-10.0/commandimportance-ru-986d64839edb-b052cb1f3abba688.md); [buttonkind-ru-d5e4639dfe25-358dae5217998b76](../../raw/text-10.0/buttonkind-ru-d5e4639dfe25-358dae5217998b76.md); [autofillcontentkind-ru-82cff6e2c109-bdd1f54e57d97127](../../raw/text-10.0/autofillcontentkind-ru-82cff6e2c109-bdd1f54e57d97127.md); [tableargument-ru-7c7dcf0a50be-97126a72d5bd3d87](../../raw/text-10.0/tableargument-ru-7c7dcf0a50be-97126a72d5bd3d87.md); [arraydatasource-ru-2842d399ff6f-77471dbd5d6ca5bb](../../raw/text-10.0/arraydatasource-ru-2842d399ff6f-77471dbd5d6ca5bb.md); [collectionfieldcomparisonkind-ru-536c6e862fc9-0dc18f981db63f0b](../../raw/text-10.0/collectionfieldcomparisonkind-ru-536c6e862fc9-0dc18f981db63f0b.md); [treedatasource-ru-367f34c33419-84e906ee22ce1d87](../../raw/text-10.0/treedatasource-ru-367f34c33419-84e906ee22ce1d87.md); [dialog-ru-c77b85fd9948-50f83cd1a79bdddd](../../raw/text-10.0/dialog-ru-c77b85fd9948-50f83cd1a79bdddd.md); [clientlogevent-ru-d2cc346d9592-ec3f1cda21853e62](../../raw/text-10.0/clientlogevent-ru-d2cc346d9592-ec3f1cda21853e62.md); [userfavoritesimportance-ru-55a73563da0e-f33524a0b4fbdec6](../../raw/text-10.0/userfavoritesimportance-ru-55a73563da0e-f33524a0b4fbdec6.md); [fileschoice-ru-65be716cb62b-7f7e591377f1eb9e](../../raw/text-10.0/fileschoice-ru-65be716cb62b-7f7e591377f1eb9e.md); [filteritemgroupkind-ru-cd2e5290861b-1e375a45bea1b945](../../raw/text-10.0/filteritemgroupkind-ru-cd2e5290861b-1e375a45bea1b945.md); [formsectionarea-ru-28eb27fc3e33-ddc0ac6177256e7f](../../raw/text-10.0/formsectionarea-ru-28eb27fc3e33-ddc0ac6177256e7f.md); [treeschemalayoutkind-ru-8620e90de67c-1f1a893e415c9b02](../../raw/text-10.0/treeschemalayoutkind-ru-8620e90de67c-1f1a893e415c9b02.md); [matrixgroupautofill-ru-e1d5cd00988f-099938302e4f86a9](../../raw/text-10.0/matrixgroupautofill-ru-e1d5cd00988f-099938302e4f86a9.md); [carouselnavigationkind-ru-9949a7cb768c-cf4eee97733a424d](../../raw/text-10.0/carouselnavigationkind-ru-9949a7cb768c-cf4eee97733a424d.md); [userworkhistory-ru-ad103b9e3c6d-c63c1f30c7c0e627](../../raw/text-10.0/userworkhistory-ru-ad103b9e3c6d-c63c1f30c7c0e627.md); [jsexecutionexception-ru-436350b62184-465f86946435db9e](../../raw/text-10.0/jsexecutionexception-ru-436350b62184-465f86946435db9e.md); [kanbanboard-ru-1b93e2ef9d81-f27c5b36d55dcf73](../../raw/text-10.0/kanbanboard-ru-1b93e2ef9d81-f27c5b36d55dcf73.md); [rowautoselection-ru-e2fbed1c50a8-3ac12a55f9d366d4](../../raw/text-10.0/rowautoselection-ru-e2fbed1c50a8-3ac12a55f9d366d4.md); [securestorage-ru-43304fadc791-c13e0244fa13eb96](../../raw/text-10.0/securestorage-ru-43304fadc791-c13e0244fa13eb96.md); [commandinterface-afb26dc43e4a-52c0a78d931bf80a](../../raw/text-10.0/commandinterface-afb26dc43e4a-52c0a78d931bf80a.md); [xychart-ru-c886ec1c03f7-9e2550195c68909c](../../raw/text-10.0/xychart-ru-c886ec1c03f7-9e2550195c68909c.md); [commandwithcomponentname-ru-d0473609c32f-220fce3cdb1ab8e5](../../raw/text-10.0/commandwithcomponentname-ru-d0473609c32f-220fce3cdb1ab8e5.md); [geographicmaps-e9b51cd385de-d09b8df2c5ce6ef6](../../raw/text-10.0/geographicmaps-e9b51cd385de-d09b8df2c5ce6ef6.md); [automatic-interface-df2ea881a675-63226f4f9962580e](../../raw/text-10.0/automatic-interface-df2ea881a675-63226f4f9962580e.md); [commandwithcomponent-ru-bd6661ad8549-67d185bf3571b2bc](../../raw/text-10.0/commandwithcomponent-ru-bd6661ad8549-67d185bf3571b2bc.md)
> Updated: 2026-10-05

Версия: `10.0`.

## Тематические объяснения

- [Тип компонента, экземпляр и наследование](component-model.md) — Как компонент становится видимым и как связаны описание и код.
- [Выбор компонентов для формы](component-choice.md) — Контейнеры, ввод, действия и отображение списков.
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md) — Наблюдаемые свойства, выражения и автоматический пересчёт.
- [События компонентов и обработчики](events-and-handlers.md) — Назначение обработчиков и связь пользовательских событий с кодом.
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md) — Источник, поля, колонки и фильтр: переход от данных к отображению списка.

## Оглавление справочника

Счётчики рассчитаны по реестру покрытия. Точные источники каждого описания находятся в соответствующем групповом индексе.

| Группа | Статей |
| --- | ---: |
| [Руководство разработчика](index-guide-01.md) | 79 |
| [XBSL: Std::GeographicMaps](index-xbsl-geographicmaps-01.md) | 11 |
| [XBSL: Std::GeographicMaps::Interface](index-xbsl-geographicmaps-interface-01.md) | 5 |
| [XBSL: Std::Interface](index-xbsl-interface-01.md) | 49 |
| [XBSL: Std::Interface::Charts](index-xbsl-interface-charts-01.md) | 35 |
| [XBSL: Std::Interface::ClientApplication](index-xbsl-interface-clientapplication-01.md) | 27 |
| [XBSL: Std::Interface::ClientDevice](index-xbsl-interface-clientdevice-01.md) | 9 |
| [XBSL: Std::Interface::Commands](index-xbsl-interface-commands-01.md) | 10 |
| [XBSL: Std::Interface::CommonComponents](index-xbsl-interface-commoncomponents-01.md) | 33 |
| [XBSL: Std::Interface::DataInput](index-xbsl-interface-datainput-01.md) | 14 |
| [XBSL: Std::Interface::DataSources](index-xbsl-interface-datasources-01.md) | 4 |
| [XBSL: Std::Interface::DataSources::Array](index-xbsl-interface-datasources-array-01.md) | 2 |
| [XBSL: Std::Interface::DataSources::DynamicList](index-xbsl-interface-datasources-dynamiclist-01.md) | 13 |
| [XBSL: Std::Interface::DataSources::Tree](index-xbsl-interface-datasources-tree-01.md) | 6 |
| [XBSL: Std::Interface::Dialogs](index-xbsl-interface-dialogs-01.md) | 3 |
| [XBSL: Std::Interface::Events](index-xbsl-interface-events-01.md) | 1 |
| [XBSL: Std::Interface::Favorites](index-xbsl-interface-favorites-01.md) | 8 |
| [XBSL: Std::Interface::Files](index-xbsl-interface-files-01.md) | 8 |
| [XBSL: Std::Interface::Filters](index-xbsl-interface-filters-01.md) | 9 |
| [XBSL: Std::Interface::Forms](index-xbsl-interface-forms-01.md) | 16 |
| [XBSL: Std::Interface::GraphicalSchemas](index-xbsl-interface-graphicalschemas-01.md) | 9 |
| [XBSL: Std::Interface::Groups](index-xbsl-interface-groups-01.md) | 15 |
| [XBSL: Std::Interface::Groups::Carousel](index-xbsl-interface-groups-carousel-01.md) | 5 |
| [XBSL: Std::Interface::History](index-xbsl-interface-history-01.md) | 2 |
| [XBSL: Std::Interface::HtmlEmbedding](index-xbsl-interface-htmlembedding-01.md) | 3 |
| [XBSL: Std::Interface::KanbanBoard](index-xbsl-interface-kanbanboard-01.md) | 9 |
| [XBSL: Std::Interface::Lists](index-xbsl-interface-lists-01.md) | 20 |
| [XBSL: Std::Interface::SecureStorage](index-xbsl-interface-securestorage-01.md) | 3 |
| [Каталоги справочников](index-catalogs-01.md) | 3 |
| [Настройки компонентов](index-components-01.md) | 89 |
| [Прикладные и генерируемые типы XBSL](index-generated-01.md) | 5 |
| [Пространства имён XBSL](index-namespaces-01.md) | 27 |
| [Термины](index-glossary-01.md) | 12 |
| [Элементы проекта](index-elements-01.md) | 12 |

## See Also

- [Общий индекс](../index.md)
- [Пространства имён](../stdlib/namespaces.md)
- [Компоненты: руководство и контракты](../interface/component-map.md)
- [Элементы проекта и порождаемые типы](../project/element-map.md)
