# ПараметрСамостоятельнойРегистрацииПользователя

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [userselfregistrationparameter-d7c7b1146099-133e998f4fa59099](../../raw/text-10.0/userselfregistrationparameter-d7c7b1146099-133e998f4fa59099.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Элемент проекта.

Имена для поиска: `ПараметрСамостоятельнойРегистрацииПользователя`, `UserSelfRegistrationParameter`, `Std::ProjectElements::UserSelfRegistrationParameter`.

## Обзор

Элемент проекта, позволяющий передать процессу самостоятельной регистрации пользователя дополнительные данные ([подробнее](https://1cmycloud.com/console/help/element/10.0/docs/topics/self-registration-form/#%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0-%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D1%81%D0%B0%D0%BC%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%D1%80%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D0%B8%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)).

## Документированный контракт и примеры

Элемент проекта, позволяющий передать процессу самостоятельной регистрации пользователя дополнительные данные ([подробнее](https://1cmycloud.com/console/help/element/10.0/docs/topics/self-registration-form/#%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0-%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D1%81%D0%B0%D0%BC%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%D1%80%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D0%B8%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)).

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### ОбластьВидимости

```yaml
ОбластьВидимости: ОбластьВидимости
```

[Видимость](../language/modular-development-80166cfecf93.md) элемента проекта:

- [ВПодсистеме](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден внутри одной подсистемы во всех пакетах (значение по умолчанию);
- [ВПроекте](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах одного проекта;
- [Глобально](../project/visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах всех проектов.

---

#### Импорт

```yaml
Импорт: ПространствоИмен[]
```

Список [импортированных пространств имен](../language/modular-development-80166cfecf93.md).

---

## Дочерние элеметы

#### Поля

```yaml
Поля: ПараметрПоляСаморегистрацииПользователя[]
```

Описание полей параметра.

---

## See Also

- [Навигатор раздела](../security/overview.md)
- [Ключи доступа и разрешения приложения](../security/access-keys-and-permissions.md)

Оригинал: [ПараметрСамостоятельнойРегистрацииПользователя](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/UserSelfRegistrationParameter/).
