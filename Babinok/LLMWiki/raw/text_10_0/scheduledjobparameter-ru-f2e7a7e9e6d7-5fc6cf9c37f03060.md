# ПараметрЗапланированногоЗадания

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/ScheduledJob/Parameters/ScheduledJobParameter_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/ScheduledJob/Parameters/ScheduledJobParameter_ru/index.html
> SHA256: 04b3ec5330827e8e0a30b83a4ed2856acf5f2be6094131e3991934fc556010cc
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Параметр, используемый при выполнении запланированного задания.

---

## Свойства

#### Имя

```yaml
Имя: Строка
```

Имя элемента.

---

#### Значение

```yaml
Значение: Объект
```

Значение параметра, которое будет использоваться при вызове предопределенного задания или задания, созданного в модуле по шаблону без переопределения параметров. Если значение не указано, будет использоваться значение по умолчанию для типа. Если у типа нет значения по умолчанию, то значение параметра должно быть указано при создании задания.

Если для какого-либо параметра не задано значение, то для такого задания свойство [ПредопределенноеЗадание](../../wiki/project/scheduledjob-82127f45462a.md) может иметь только значение **НеСоздавать**.

---

#### Тип

```yaml
Тип: Тип[]
```

Тип параметра.

---
