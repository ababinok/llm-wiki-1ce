# ПроизвольнаяВстроеннаяВебСтраница

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [customembeddedwebpage-ru-b6450f3540f4-49ad10bb909b3a9c](../../raw/text-10.0/customembeddedwebpage-ru-b6450f3540f4-49ad10bb909b3a9c.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Настройки компонента.

Владелец: StandardClientApplicationWithSections / EmbeddedWebPages / EmbeddedWebPagesInstance / WebPages.

Имена для поиска: `ПроизвольнаяВстроеннаяВебСтраница`, `CustomEmbeddedWebPage`, `Std::InterfaceComponents::StandardClientApplicationWithSections::EmbeddedWebPages::EmbeddedWebPagesInstance::WebPages::CustomEmbeddedWebPage`.

## Обзор

Осуществляет взаимодействие с произвольной встроенной веб-страницей внутри приложения типа [СтандартноеКлиентскоеПриложениеСРазделами](standardclientapplicationwithsections-fd5fbdc63cd1.md).

## Документированный контракт и примеры

Осуществляет взаимодействие с произвольной встроенной веб-страницей внутри приложения типа [СтандартноеКлиентскоеПриложениеСРазделами](standardclientapplicationwithsections-fd5fbdc63cd1.md).

---

## Свойства

#### Url

```yaml
Url: ВычисляемоеВыражение|Строка
```

Адрес встроенной веб-страницы, с которой осуществляется взаимодействие.

---

#### Данные

```yaml
Данные: ВычисляемоеВыражение|Объект?
```

Дополнительная информация о встроенной веб-странице.

---

#### Ид

```yaml
Ид: ВычисляемоеВыражение|Строка
```

Идентификатор встроенной веб-страницы.

---

#### Изображение

```yaml
Изображение: ВычисляемоеВыражение|Url|ДвоичныйОбъект.Ссылка|?
```

Иконка встроенной веб-страницы.

---

#### Представление

```yaml
Представление: ВычисляемоеВыражение|Строка
```

Текстовое представление встроенной веб-страницы в интерфейсе.

---

#### ПриНачалеЗагрузки

```yaml
ПриНачалеЗагрузки: Строка
```

Подключает обработчик, вызываемый при начале загрузки встроенной веб-страницы.

---

#### ПриОткрытии

```yaml
ПриОткрытии: Строка
```

Подключает обработчик, вызываемый при получении от встроенной веб-страницы информации о ее фактическом старте и готовности к работе.

---

#### ПриПолученииСообщения

```yaml
ПриПолученииСообщения: Строка
```

Подключает обработчик, вызываемый при получении сообщения от встроенной веб-страницы.

---

## Дочерние элеметы

#### КомпонентСостоянияЗагрузки

```yaml
КомпонентСостоянияЗагрузки: Компонент?
```

Устанавливает экран загрузки для встроенной веб-страницы.

---

## See Also

- [Навигатор раздела](overview.md)
- [ВебСтраницы — Настройки компонента: StandardClientApplicationWithSections / EmbeddedWebPages / EmbeddedWebPagesInstance](webpages-5c9029b311f5.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [ПроизвольнаяВстроеннаяВебСтраница](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/InterfaceComponents/Std/InterfaceComponents/StandardClientApplicationWithSections/EmbeddedWebPages/EmbeddedWebPagesInstance/WebPages/CustomEmbeddedWebPage_ru/).
