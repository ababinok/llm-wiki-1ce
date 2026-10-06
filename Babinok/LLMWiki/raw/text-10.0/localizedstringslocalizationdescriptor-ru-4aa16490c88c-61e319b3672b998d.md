# Локализация

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/LocalizedStringsLocalizationDescriptor_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/LocalizedStringsLocalizationDescriptor_ru/index.html
> SHA256: 974f13bdcd37e4d9dcf3aafa9c3882ad327b95a2466dd17c028e535d9707da74
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Предназначен для хранения значений локализуемых строк на другом языке (язык может быть только тот, который указан в описании проекта в свойстве [ЯзыкиЛокализации](../../wiki/project/projectdescriptor-d54722c348c7.md)). Элемент локализации содержит только разделы с ключами и значениями локализуемых строк.

---

## Свойства

#### Строки

```yaml
Строки: Соответствие<Строка,Строка>
```

Строки, которые должны быть переведены на другие языки. Для каждой строки указывается ее ключ (идентификатор) и значение. Строки можно использовать в описании компонентов интерфейса и элементов проекта, а также в коде.

---

#### Шаблоны

```yaml
Шаблоны: Соответствие<Строка,Строка>
```

Локализуемые строковые шаблоны, в которые можно подставлять значения переменных. Для каждого шаблона указывается его ключ (идентификатор) и значение. Шаблоны можно использовать только в коде.

---
