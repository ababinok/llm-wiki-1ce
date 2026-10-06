# Общие сведения о пользовательском интерфейсе приложения

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [application-ui-overview-0af555da9f86-0bf7d09cfa64412a](../../raw/text-10.0/application-ui-overview-0af555da9f86-0bf7d09cfa64412a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Общие сведения о пользовательском интерфейсе приложения`, `application-ui-overview`.

## Обзор

Пользовательский интерфейс приложения — это набор визуальных элементов, который позволяет пользователю взаимодействовать с приложением.

## Документированный контракт и примеры

Пользовательский интерфейс приложения — это набор визуальных элементов, который позволяет пользователю взаимодействовать с приложением. «1С:Предприятие.Элемент» предоставляет модель построения пользовательского интерфейса. Эта модель основана на том, что вы описываете интерфейс в виде набора экземпляров компонентов. Компоненты могут быть системными (определенными в «1С:Предприятие.Элементе») или вашими собственными компонентами интерфейса, добавленными в проект (унаследованными от системных компонентов).

## Внешний вид интерфейса

Если ваш проект содержит только функциональные элементы и не содержит компонентов интерфейса, вы можете запустить приложение и работать с ним, потому что «1С:Предприятие.Элемент» сгенерирует для него автоматический интерфейс ([подробнее](auto-generated-ui-7150689c0714.md)).

Создавая интерфейс приложения, вы можете использовать готовые «шаблоны» интерфейса, содержащие набор стандартных областей ([подробнее](standard-client-application-with-sections-component-49da52beb720.md)).

## Пользовательский интерфейс

Все визуальные элементы, предназначенные для показа информации пользователю и для изменения этой информации, относятся к пользовательскому интерфейсу. В «1С:Предприятие.Элементе» существует большое количество системных компонентов для построения пользовательского интерфейса. Вы можете использовать непосредственно их или создавать собственные компоненты интерфейса, наследуя их от системных.

## Командный интерфейс

Кнопки, ссылки, команды, которые позволяют пользователю перемещаться по разделам приложения, открывать формы, выполнять те или иные действия, относятся к командному интерфейсу. Для формирования командного интерфейса существует несколько видов элементов проекта, которые вы можете использовать по отдельности или собирать во фрагменты командного интерфейса ([подробнее](command-interface-9e5d023134de.md)).

## Клиентское приложение

[СтандартноеКлиентскоеПриложениеСРазделами](standard-client-application-with-sections-component-49da52beb720.md)

[ПроизвольноеКлиентскоеПриложение](custom-client-application-component-a5e093d01cdd.md)

## Формы и окна

[Форма](form-component-975c31cd89e9.md)

[ФормаОбъекта](object-form-component-98dd1d49f7f9.md)

[ФормаСписка](list-form-component-69a3ee661728.md)

## Группировка и размещение компонентов

[Страницы](pages-component-7af79e372a20.md)

[Страница](page-component-5977250eb3da.md)

[СворачиваемыйКомпонент](collapsible-component-eaeea15932b4.md)

[Группа](group-component-982f449c1db4.md)

[СтековаяГруппа](stack-group-component-48fe87212e32.md)

[ГруппаСписокСДеталями](list-with-details-group-component-5a6bc6a119e6.md)

[ГруппаСПлавающимКомпонентом](group-with-floating-component-52894d8d3fb8.md)

## Таблицы и списки

[Таблица](../project/table-overview-0bc2ec1e1bb3.md)

[СтандартнаяКолонкаТаблицы](standardtablecolumn-ru-0b1e3e80ca73.md)

[ПроизвольнаяКолонкаТаблицы](customtablecolumn-ru-51fab442bbf8.md)

[СтандартныйСписок](standardlist-ru-1010f63ab92e.md)

[ПроизвольныйСписок](customlist-ru-89d83d55b4b0.md)

[ПроизвольнаяСтрокаСписка](customlistrow-ru-3ccc8ad55f87.md)

## Стандартные компоненты

[ПолеВвода](edit-component-a54ad83ade7f.md)

[Надпись](label-component-975bcb38121f.md)

[СтандартнаяКарточка](standard-card-component-12665d7eda6b.md)

[ПроизвольнаяКарточка](custom-card-component-b505ea7a5b7d.md)

[Флажок](checkbox-component-28feae196391.md)

[РадиоКнопка](radio-button-component-6d172cc50293.md)

[Кнопка](button-component-9e3a091652f8.md)

[ПлавающаяКнопка](floating-button-component-acb0efab6cf6.md)

[Картинка](picture-component-29da1046d860.md)

[КомпонентВыбора](choice-component-1e3167cb37d2.md)

[ВсплывающееМеню](popup-menu-component-b6a2f8edad85.md)

[ВсплывающийКомпонент](popup-component-a3b47b93a600.md)

[ВыборДатыВремени](date-time-choice-component-6b891eec73f9.md)

[ВыборФайлов](files-choice-component-f28c0737018e.md)

[КонтейнерHtml](html-container-component-07a59cecebfd.md)

[ФорматированныйДокумент](formatted-document-component-adfc034f4ad2.md)

[ПросмотрPdf](pdf-view-component-2aa10f00a4db.md)

[ПанельТегов](tag-panel-74f7123dd302.md)

[ПанельЭтапов](stages-panel-646f68c7051d.md)

[ГеографическаяКарта](geographic-map-dc6f2bf9f705.md)

[СтандартноеОкноМаркераГеографическойКарты](geographic-map-dc6f2bf9f705.md)

[ПроизвольноеОкноМаркераГеографическойКарты](geographic-map-dc6f2bf9f705.md)

[КанбанДоска](kanban-board-e9a1a24f61cd.md)

[СтандартнаяКанбанКарточка](kanban-board-e9a1a24f61cd.md)

[ПроизвольнаяКанбанКарточка](kanban-board-e9a1a24f61cd.md)

## Команды

### Группы команд

[ФрагментКомандногоИнтерфейса](command-interface-fragment-f742e5d6797f.md)

[ГруппаКомандногоИнтерфейса](command-interface-group-52b75d5d03e9.md)

### Одиночные команды

[НавигационнаяКоманда](../project/navigation-command-e62fae29cc19.md)

[ОбычнаяКоманда](../language/usual-command-5d6bb6c02c99.md)

[ПереключаемаяКоманда](../language/switchable-command-71037e8e27ae.md)

[КомандаСКомпонентом](command-with-component-7c947b7abad5.md)

[КомандаСПараметром](command-with-parameter-37e448e97dea.md)

## Отчеты

[ФормаОтчета](display-reports-in-user-interface-c28b42e53b7f.md)

[ПросмотрОтчета](display-reports-in-user-interface-c28b42e53b7f.md)

## Диаграммы

[XYДиаграмма](xy-chart-component-39ac97259e35.md)

[ВоронкообразнаяДиаграмма](funnel-chart-component-fa49bd9425cf.md)

[ДиаграммаГанта](gantt-chart-component-d69f4f5486d2.md)

[КруговаяДиаграмма](pie-chart-component-8d4b05819515.md)

[Органиграмма](organigram-component-27492eec96dc.md)

## See Also

- [Навигатор раздела](overview.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [Общие сведения о пользовательском интерфейсе приложения](https://1cmycloud.com/console/help/element/10.0/docs/topics/application-ui-overview/).
