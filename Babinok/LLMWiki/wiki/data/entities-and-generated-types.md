# Хранимые данные и порождаемые типы

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [catalog-project-element-b6ca52d114d4-05a6ee60331e001e](../../raw/text-10.0/catalog-project-element-b6ca52d114d4-05a6ee60331e001e.md); [ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1](../../raw/figures/ea47b2e45b6c8cabb1c05c6b5127135a0328d945fc00081598645499c6f19768-059090e7b036e8b1.md); [catalog-types-e0c7c64f0c49-c147cf951d586e7f](../../raw/text-10.0/catalog-types-e0c7c64f0c49-c147cf951d586e7f.md); [d592c49107ec12d51723cd79e3c7a323945cf1dae8a620ad57b98930dd3d3a66-c8d16e549efd354b](../../raw/figures/d592c49107ec12d51723cd79e3c7a323945cf1dae8a620ad57b98930dd3d3a66-c8d16e549efd354b.md); [8295d0ebe7a31b334ef3ba92c243f5f0b79108d557c9e6fcea34baade73eb763-cfd6b589c72b1e90](../../raw/figures/8295d0ebe7a31b334ef3ba92c243f5f0b79108d557c9e6fcea34baade73eb763-cfd6b589c72b1e90.md); [ec539f819e6ee01d2d6b3bb8b48db3181272c1d777412f667baf6697be1bc180-cac8878202623b73](../../raw/figures/ec539f819e6ee01d2d6b3bb8b48db3181272c1d777412f667baf6697be1bc180-cac8878202623b73.md); [information-register-project-element-8932693c91b1-c99ced82cebe5efb](../../raw/text-10.0/information-register-project-element-8932693c91b1-c99ced82cebe5efb.md); [information-register-types-a915e7f32292-9712d4fe3e6872bb](../../raw/text-10.0/information-register-types-a915e7f32292-9712d4fe3e6872bb.md); [47a8cffd8ed46c0235149186d74e02b444b6b2f359346d4d906effcf71a06c2d-d7789fa9de9c1197](../../raw/figures/47a8cffd8ed46c0235149186d74e02b444b6b2f359346d4d906effcf71a06c2d-d7789fa9de9c1197.md); [51beecf5e85cd14e8e97fe4249d86eb278060aa2c86a2673634a7bf01fed413b-1782d47b089376c0](../../raw/figures/51beecf5e85cd14e8e97fe4249d86eb278060aa2c86a2673634a7bf01fed413b-1782d47b089376c0.md); [b2694f8d8141a285d572d3e9927d24eb7461ec32135a4b5f8108f013fc1a21c1-8e9bf4e1c356b572](../../raw/figures/b2694f8d8141a285d572d3e9927d24eb7461ec32135a4b5f8108f013fc1a21c1-8e9bf4e1c356b572.md); [a2e108680242e03d50691995c0fc7c9f2827ce9d0f52a5e68fa492103cdbebca-f277e949ae6ebfdc](../../raw/figures/a2e108680242e03d50691995c0fc7c9f2827ce9d0f52a5e68fa492103cdbebca-f277e949ae6ebfdc.md); [5b56aa264ccc47b65ce43c6ea4239ae0a766a97d73ffa1d223f11168102cd247-6c69cdc4a14e74f7](../../raw/figures/5b56aa264ccc47b65ce43c6ea4239ae0a766a97d73ffa1d223f11168102cd247-6c69cdc4a14e74f7.md)
> Updated: 2026-10-05

Версия: `10.0`.

## Обзор

Справочник описывает набор элементов с реквизитами. У элемента справочника есть уникальный идентификатор — ссылка. Регистр сведений хранит информацию, организованную через измерения, ресурсы и реквизиты. Эти механизмы следует выбирать по модели данных приложения.

## Справочник и его типы

Описание справочника порождает несколько типов. Для справочника `Сотрудники` документация показывает `Сотрудники`, `Сотрудники.Ссылка`, `Сотрудники.Объект` и `Сотрудники.Данные`. Тип с именем справочника является типом-одиночкой и содержит методы работы с элементами и ссылками.

Проверяйте контракт именно того типа, с которым работает код: ссылка, объект и данные не являются взаимозаменяемыми обозначениями. Подробные сигнатуры и примеры находятся в статье о порождаемых типах.

## Регистр сведений

Измерения задают значения, для которых хранится информация; ресурсы содержат основную информацию, а реквизиты — дополнительные сведения. Порождаемые типы и операции регистра проверяйте по его отдельному справочнику.

## Связь с интерфейсом и запросами

Для показа данных в форме нужен компонент и его источник данных. Для выборки в коде используйте документированные механизмы запросов и учитывайте окружение исполнения и права доступа.

## Документация и примеры

- [Элемент проекта вида «Справочник» — Руководство](catalog-project-element-b6ca52d114d4.md)
- [Типы, порождаемые элементом проекта вида «Справочник» — Руководство](catalog-types-e0c7c64f0c49.md)
- [Элемент проекта вида «РегистрСведений» — Руководство](information-register-project-element-8932693c91b1.md)
- [Типы, порождаемые элементом проекта вида «РегистрСведений» — Руководство](information-register-types-a915e7f32292.md)

## See Also

- [Навигатор раздела](overview.md)
- [typed-and-dynamic-queries](../queries/typed-and-dynamic-queries.md)
- [component-choice](../interface/component-choice.md)
- [access-keys-and-permissions](../security/access-keys-and-permissions.md)
