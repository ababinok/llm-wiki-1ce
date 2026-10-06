# КомпонентСамостоятельнойРегистрации

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/xbsl/Std/Users/SelfService/Interface/SelfRegistrationComponent_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/xbsl/Std/Users/SelfService/Interface/SelfRegistrationComponent_ru/index.html
> SHA256: bca5fc012a94bc2a586c945bc0e7e2941dd0295787d70e7a75e0f8fa1d8c06e8
> SnapshotCreated: 2026-10-05
> Rendition: verified text

`Стд::Пользователи::Самообслуживание::Интерфейс::КомпонентСамостоятельнойРегистрации` `Доступность: Клиент`

Компонент интерфейса, который с помощью API саморегистрации предоставляет пользовательский интерфейс для ввода логина, пароля, подтверждения канала связи и аутентификации через разрешенных внешних поставщиков.

**Сравнение**

Ссылочное

## Иерархия типа

*Базовые типы:* [Группа](../../wiki/interface/group-ru-9e7fcb6be273.md), [Компонент](../../wiki/interface/component-ru-bad1c84be995.md), [Объект](../../wiki/stdlib/object-ru-9e351f286699.md)

---

## Свойства

### UrlПослеРегистрации

`Доступность: Клиент`

```
UrlПослеРегистрации: Строка?
```

Относительный URL, на который будет перенаправлен пользователь после завершения регистрации.

---

### ОтображатьФормуРедактированияПользовательскихДанныхОтдельно

`Доступность: Клиент`

```
ОтображатьФормуРедактированияПользовательскихДанныхОтдельно: Булево
```

Определяет, как отображать форму редактирования пользовательских данных (если она задана). Если значение свойства равно **Ложь** (значение по умолчанию), то форма отображается вместе с формой ввода логина. Если **Истина**, то форма редактирования пользовательских данных отображается на отдельной странице.

Рекомендуется использовать значение **Ложь** для форм с небольшим количеством полей (1-2). Если полей ввода много, то лучше отображать форму редактирования пользовательских данных отдельно.

---

### ФормаРедактированияПользовательскихДанных

`Доступность: Клиент`

```
ФормаРедактированияПользовательскихДанных: ФормаРедактированияПользовательскихДанных?
```

Форма заполнения данных пользователя. Заполненные данные будут использоваться при регистрации.

Тип, реализующий контракт, должен быть компонентом интерфейса, иначе при открытии компонента регистрации будет выброшено исключение.

---

## Методы

### УстановитьЛогинИКонтакт

`Доступность: Клиент`

```
УстановитьЛогинИКонтакт(
  Логин: Строка,
  ВидКонтакта: ВидКонтактнойИнформации,
  Контакт: Строка)
```

Позволяет установить логин и контакт. Удобно использовать при переходе по ссылке на приложение.

Если используется данный метод, при регистрации пользователя пропускается выбор способов регистрации и при заполнении данных для регистрации по логину и паролю становится недоступно редактирование логина и контакта.

---

## Список унаследованных методов

### Компонент

[Активировать](../../wiki/interface/component-ru-bad1c84be995.md)

[ОтключитьОбработчикТаймера](../../wiki/interface/component-ru-bad1c84be995.md)

[ПодключитьОбработчикТаймера](../../wiki/interface/component-ru-bad1c84be995.md)

### Объект

[ВСтроку](../../wiki/stdlib/object-ru-9e351f286699.md)

[ПолучитьТип](../../wiki/stdlib/object-ru-9e351f286699.md)

[Представление](../../wiki/stdlib/object-ru-9e351f286699.md)

## Список унаследованных свойств

### Группа

[ВыравниваниеСодержимогоПоВертикали](../../wiki/interface/group-ru-9e7fcb6be273.md), [ВыравниваниеСодержимогоПоГоризонтали](../../wiki/interface/group-ru-9e7fcb6be273.md), [Заголовок](../../wiki/interface/group-ru-9e7fcb6be273.md), [ИнтервалМеждуЭлементамиПоВертикали](../../wiki/interface/group-ru-9e7fcb6be273.md), [ИнтервалМеждуЭлементамиПоГоризонтали](../../wiki/interface/group-ru-9e7fcb6be273.md), [Команды](../../wiki/interface/group-ru-9e7fcb6be273.md), [Компоновка](../../wiki/interface/group-ru-9e7fcb6be273.md), [НастройкиКарусели](../../wiki/interface/group-ru-9e7fcb6be273.md), [НастройкиКомпоновкиБенто](../../wiki/interface/group-ru-9e7fcb6be273.md), [НастройкиМатричнойКомпоновки](../../wiki/interface/group-ru-9e7fcb6be273.md), [ОтображатьЗаголовок](../../wiki/interface/group-ru-9e7fcb6be273.md), [ОтображатьРазделитель](../../wiki/interface/group-ru-9e7fcb6be273.md), [ОтступПоВертикали](../../wiki/interface/group-ru-9e7fcb6be273.md), [ОтступПоГоризонтали](../../wiki/interface/group-ru-9e7fcb6be273.md), [Подвал](../../wiki/interface/group-ru-9e7fcb6be273.md), [ПодвалСвернут](../../wiki/interface/group-ru-9e7fcb6be273.md), [ПрокруткаПоВертикали](../../wiki/interface/group-ru-9e7fcb6be273.md), [ПрокруткаПоГоризонтали](../../wiki/interface/group-ru-9e7fcb6be273.md), [Рамка](../../wiki/interface/group-ru-9e7fcb6be273.md), [Содержимое](../../wiki/interface/group-ru-9e7fcb6be273.md), [ЦветРамки](../../wiki/interface/group-ru-9e7fcb6be273.md), [ЦветФона](../../wiki/interface/group-ru-9e7fcb6be273.md), [ШрифтЗаголовка](../../wiki/interface/group-ru-9e7fcb6be273.md)

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)

## Список унаследованных событий

### Компонент

[ВесПриРастягивании](../../wiki/interface/component-ru-bad1c84be995.md), [Видимость](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [ВыравниваниеВГруппеПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [Высота](../../wiki/interface/component-ru-bad1c84be995.md), [Доступность](../../wiki/interface/component-ru-bad1c84be995.md), [ЕстьНаведение](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МаксимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяВысота](../../wiki/interface/component-ru-bad1c84be995.md), [МинимальнаяШирина](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоВертикали](../../wiki/interface/component-ru-bad1c84be995.md), [РастягиватьПоГоризонтали](../../wiki/interface/component-ru-bad1c84be995.md), [ТолькоЧтение](../../wiki/interface/component-ru-bad1c84be995.md), [Ширина](../../wiki/interface/component-ru-bad1c84be995.md), [ШиринаВКолонках](../../wiki/interface/component-ru-bad1c84be995.md)
