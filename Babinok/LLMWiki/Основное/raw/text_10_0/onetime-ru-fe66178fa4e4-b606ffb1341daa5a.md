# Однократно

> Source: https://1cmycloud.com/console/help/element/10.0/docs/stdlib/element/ProjectElements/Std/ProjectElements/ScheduledJob/Schedule/OneTime_ru/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/stdlib/element/ProjectElements/Std/ProjectElements/ScheduledJob/Schedule/OneTime_ru/index.html
> SHA256: fb65299916d5f464b0ca0e92817f1e1daed5085d2d9170409a1ec1e2c4e202a3
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Расписание однократного запуска задания.

---

## Свойства

#### ЗапуститьВ

```yaml
ЗапуститьВ: Момент
```

Момент запуска задания.

---

#### ВремяНачала

```yaml
ВремяНачала: Момент
```

Момент, после наступления которого задание начнет запускаться. Если значение не задано, то начинать запуск немедленно.

---

#### ВремяКонца

```yaml
ВремяКонца: Момент|Время
```

Момент/время, после наступления которого задание прекратит запускаться. Если значение не задано, то запускать бесконечно.

---

#### ИсполнятьПропущенное

```yaml
ИсполнятьПропущенное: Булево
```

Признак того, что задание нужно запустить после старта приложения, если в указанный в расписании момент времени приложение было остановлено.

---
