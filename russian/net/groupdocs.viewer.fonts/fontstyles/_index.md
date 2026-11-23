---
title: "FontStyles"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет 4 возможных стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic"
type: docs
weight: 810
url: /ru/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

Представляет 4 возможных стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic.

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | Создаёт один экземпляр [`FontStyles`](../fontstyles) из указанных флагов bold и italic |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | Указывает, имеет ли этот экземпляр [`FontStyles`](../fontstyles) флаг **bold**, включённый (`true`) или отключённый (`false`) |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | Указывает, имеет ли этот экземпляр [`FontStyles`](../fontstyles) флаг **italic**, включённый (`true`) или отключённый (`false`) |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | Имя этого стиля шрифта |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | Указывает, равен ли этот экземпляр [`FontStyles`](../fontstyles) указанному |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | Указывает, равен ли этот экземпляр [`FontStyles`](../fontstyles) указанному без приведения |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | Возвращает хеш‑код этого экземпляра |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | Возвращает имя этого стиля шрифта, то же самое, что и [`Name`](./name) |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | Пытается разобрать указанную необработанную строку как имя стиля шрифта |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | Объединяет (сливает) два указанных стиля шрифта и создаёт новый результирующий стиль шрифта, где флаги объединены (union) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | Проверяет, равны ли два значения [`FontStyles`](../fontstyles) |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | Преобразует указанный экземпляр [`FontStyles`](../fontstyles) в эквивалентный октет (8‑битовое битовое поле) в десятичном диапазоне [0..3] |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | Проверяет, не равны ли два значения [`FontStyles`](../fontstyles) |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | Вычитает второй (вычитаемый) указанный стиль шрифта из первого (вычитаемого) указанного стиля шрифта и создаёт новый результирующий стиль шрифта, в котором присутствуют только те флаги первого операнда, которые не найдены во втором операнде (разность) |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Стиль шрифта Bold (только bold, без italic) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | Стиль шрифта BoldItalic (bold и italic вместе) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Стиль шрифта Italic (только italic, без bold) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Стиль шрифта Regular, значение по умолчанию (без bold и italic) |

### Примечания

Неизменяемая структура с удобным API и операциями объединения

### См. также

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
