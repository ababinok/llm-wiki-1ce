# ПараметрыРаботыКлиента

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [clientworkparameters-199d3e9c2fb2-d0e26d3d3816ec4a](../../raw/text-10.0/clientworkparameters-199d3e9c2fb2-d0e26d3d3816ec4a.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Элемент проекта.

Имена для поиска: `ПараметрыРаботыКлиента`, `ClientWorkParameters`, `Std::ProjectElements::ClientWorkParameters`.

## Обзор

Описывает произвольный набор свойств, которые инициализируются на сервере при открытии приложения.

## Документированный контракт и примеры

Описывает произвольный набор свойств, которые инициализируются на сервере при открытии приложения. На клиенте можно получить доступ к этим свойствам.

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

- [ВПодсистеме](visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден внутри одной подсистемы во всех пакетах (значение по умолчанию);
- [ВПроекте](visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах одного проекта;
- [Глобально](visibilityscope-ru-d8260ddb99a7.md)
  
  — элемент виден во всех подсистемах всех проектов.

---

#### Импорт

```yaml
Импорт: ПространствоИмен[]
```

Список [импортированных пространств имен](../language/modular-development-80166cfecf93.md).

---

## Дочерние элеметы

#### Параметры

```yaml
Параметры: ПараметрПараметровРаботыКлиента[]
```

Содержит описание параметров.

---

## See Also

- [Навигатор раздела](overview.md)
- [{ИмяПараметровРаботыКлиента}.Параметры — Порождаемый тип XBSL: ClientWorkParametersName](../stdlib/clientworkparametersname-parameters-ru-5d5afa6451b2.md)
- [{ИмяПараметровРаботыКлиента} — Порождаемый тип XBSL: ClientWorkParametersName](../stdlib/clientworkparametersname-ru-879b332058a3.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [ПараметрыРаботыКлиента](https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/ClientWorkParameters/).
