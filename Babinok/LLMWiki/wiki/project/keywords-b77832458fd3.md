# Ключевые слова

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [keywords-b77832458fd3-1a5bf87c8b29210e](../../raw/text-10.0/keywords-b77832458fd3-1a5bf87c8b29210e.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Ключевые слова`, `keywords`.

## Обзор

Ключевые слова — это предварительно определенные зарезервированные идентификаторы, имеющие специальные значения для компилятора.

## Документированный контракт и примеры

Ключевые слова — это предварительно определенные зарезервированные идентификаторы, имеющие специальные значения для компилятора. Язык имеет несколько ключевых слов, например `если` или `возврат`, которые могут использоваться только там, где разрешает синтаксис языка программирования. Ключевые слова всегда записываются в нижнем регистре.

Некоторые ключевые слова не могут выступать в роли [имен переменных](../language/variables-d5e85cdde546.md).

Ключевые слова не могут использоваться в качестве имен элементов проекта и их составных частей, в [псевдонимах полей](select-statement-0fef6f15002c.md) и именах порождаемых типов в [литералах запроса](../queries/query-literal-4ef7a0ba981e.md), а также в значениях [свойств проекта](projectdescriptor-d54722c348c7.md) **Имя** и **Поставщик**.

Ключевые слова можно использовать как на русском, так и на английском. Можно произвольным образом смешивать язык написания ключевых слов.

В языке используются следующие ключевые слова:

| Русский язык | Английский язык | Подробнее |
| --- | --- | --- |
| `вконце` | `finally` | [Исключения](../language/exceptions-a26c3b7e6dec.md) |
| `вниз` | `down` | [Цикл `для по`](../language/for-loop-a5aca952b2be.md) |
| `возврат` | `return` | [Завершение метода и возвращаемое значение](../language/methods-in-built-in-script-language-3c568746fa15.md) |
| `выбор` | `case` | [Инструкция `выбор`](../language/case-statement-9f7b13c2d43a.md) |
| `выбросить` | `throw` | [Как вызвать исключение](../language/exceptions-a26c3b7e6dec.md) |
| `для` | `for` | [Цикл `для по`](../language/for-loop-a5aca952b2be.md) |
| `если` | `if` | [Инструкция `если`](../language/if-statement-7e14d9f942e5.md) |
| `знч` | `val` | [Объявление переменной](../language/variable-declaration-statement-defd1798c9ff.md) |
| `и` | `and` | [Булевы операции](../language/logical-and-boolean-operations-2e9bec28652f.md) |
| `из` | `in` | [Цикл `для из`](../language/for-in-loop-52f2e1fffd4d.md) |
| `или` | `or` | [Булевы операции](../language/logical-and-boolean-operations-2e9bec28652f.md) |
| `импорт` | `import` | [Инструкция `импорт`](import-statement-e99aec8efb1b.md) |
| `иначе` | `else` | [Инструкция `если`](../language/if-statement-7e14d9f942e5.md) |
| `исключение` | `exception` | [Объявление типа исключения](../language/exceptions-a26c3b7e6dec.md) |
| `исп` | `use` | [Объявление переменной](../language/variable-declaration-statement-defd1798c9ff.md) |
| `как` | `as` | [Приведение типов](../language/as-e9a5f260e5cb.md) |
| `когда` | `when` | [Инструкция `выбор`](../language/case-statement-9f7b13c2d43a.md) |
| `конст` | `const` | [Объявление переменной](../language/variable-declaration-statement-defd1798c9ff.md) |
| `конструктор` | `constructor` | [Структура](structure-a95b303918fa.md) |
| `метод` | `method` | [Определение метода](../language/methods-in-built-in-script-language-3c568746fa15.md) |
| `не` | `not` | [Булевы операции](../language/logical-and-boolean-operations-2e9bec28652f.md) |
| `неизвестно` | `unknown` | [Тип `неизвестно`](../language/unknown-type-a543abb3a169.md) |
| `ничто` | `void` | [Ключевое слово `ничто`](void-keyword-730057a75f40.md) |
| `новый` | `new` | [`новый` — операция вызова конструктора типа](../language/new-operator-647b120a7a77.md) |
| `обз` | `req` | [Структура](structure-a95b303918fa.md) |
| `область` | `scope` | [Область видимости имен](name-scope-f4e2d086669a.md) |
| `пер` | `var` | [Объявление переменной](../language/variable-declaration-statement-defd1798c9ff.md) |
| `перечисление` | `enum` | [Перечисление](../language/enumeration-type-5311bbd23ddf.md) |
| `по` | `to` | [Цикл `для по`](../language/for-loop-a5aca952b2be.md) |
| `поймать` | `catch` | [Обработка исключений](../language/exceptions-a26c3b7e6dec.md) |
| `пока` | `while` | [Цикл `пока`](../language/while-loop-a05f367321dd.md) |
| `попытка` | `try` | [Обработка исключений](../language/exceptions-a26c3b7e6dec.md) |
| `прервать` | `break` | [Циклы](../language/for-loop-a5aca952b2be.md) |
| `продолжить` | `continue` | [Циклы](../language/for-loop-a5aca952b2be.md) |
| `статический` | `static` | [Статические методы](../language/static-methods-67f66b803070.md) |
| `структура` | `structure` | [Структура](structure-a95b303918fa.md) |
| `умолчание` | `default` | [Перечисление](../language/enumeration-type-5311bbd23ddf.md) |
| `шаг` | `step` | [Цикл `для по`](../language/for-loop-a5aca952b2be.md) |
| `это` | `is` | [Проверка соответствия типу](../language/is-e12cbcb44c3d.md) |
| `этот` | `this` | [Передача модуля](../language/pass-module-as-parameter-c0872a90fb62.md) |

## See Also

- [Навигатор раздела](overview.md)
- [Как устроено приложение Элемента](application-architecture.md)

Оригинал: [Ключевые слова](https://1cmycloud.com/console/help/element/10.0/docs/topics/keywords/).
