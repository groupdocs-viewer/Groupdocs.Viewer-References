---
title: "Argb32Color"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет 32‑битный цвет в формате ARGB с 8 битами на каждый канал Альфа, Красный, Зелёный, Синий. Поддерживает прозрачность."
type: docs
weight: 950
url: /ru/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Представляет 32‑битный цвет в формате ARGB, с 8 битами на каждый канал (Alpha, Red, Green, Blue). Поддерживает прозрачность.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Получает альфа‑часть цвета как 8‑битное беззнаковое целое [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Получает альфа‑часть цвета в процентах в диапазоне (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Получает синюю часть цвета как 8‑битное беззнаковое целое [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Получает зелёную часть цвета как 8‑битное беззнаковое целое [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Указывает, является ли данный экземпляр [`Argb32Color`](../argb32color) значением по умолчанию (Прозрачный) — все 4 канала установлены в 0. То же, что и [`IsEmpty`](./isempty). |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Указывает, не инициализирован ли данный экземпляр цвета [`Argb32Color`](../argb32color) — все 4 канала установлены в 0. То же, что и значение по умолчанию и прозрачный. То же, что и [`IsDefault`](./isdefault). |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Указывает, полностью ли непрозрачен данный экземпляр [`Argb32Color`](../argb32color), без прозрачности (его альфа‑канал имеет максимальное значение). |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Указывает, полностью ли прозрачен данный экземпляр [`Argb32Color`](../argb32color) — его альфа‑канал имеет минимальное (0) значение, поэтому остальные каналы R, G и B не оказывают видимого эффекта. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Указывает, является ли данный экземпляр [`Argb32Color`](../argb32color) полупрозрачным (не полностью прозрачным, но и не полностью непрозрачным) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Возвращает красную часть цвета как 8‑битное беззнаковое целое [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Возвращает значение Int32 цвета как 32‑битное знаковое целое |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Создаёт экземпляр [`Argb32Color`](../argb32color) из его 32‑битных компонентов (альфа, красный, зелёный и синий), совместимый со значением, полученным методом `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Создаёт новый экземпляр [`Argb32Color`](../argb32color) из указанного, но с переопределённым значением альфа (непрозрачности) |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Создаёт новый экземпляр [`Argb32Color`](../argb32color) из указанного [`Rgb24Color`](../rgb24color), но с заданным значением альфа (непрозрачности) |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Создаёт одно значение [`Argb32Color`](../argb32color) из указанных каналов Red, Green, Blue, при этом канал Alpha полностью непрозрачен |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Создаёт одно значение [`Argb32Color`](../argb32color) из указанных каналов Red, Green, Blue и Alpha |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Создаёт полностью непрозрачный (A=255) цвет из единственного значения, которое будет применено ко всем каналам |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Проверяет равенство этого цвета с указанным цветом [`Argb32Color`](../argb32color) |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Проверяет этот цвет с указанным неконвертированным |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Проверяет равенство этого цвета с указанным цветом [`Rgb24Color`](../rgb24color) |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Возвращает светлоту/яркость Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Argb32Color`](../argb32color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Возвращает хеш‑код, определяющий текущий цвет. Не совместим с GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Возвращает значение оттенка Hue‑Saturation‑Lightness (HSL) в градусах для данного экземпляра [`Argb32Color`](../argb32color). Если R == G == B, оттенок не имеет смысла, и возвращаемое значение равно 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | Насыщенность Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Argb32Color`](../argb32color) |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Возвращает значение ARGB данного экземпляра [`Argb32Color`](../argb32color), совместимое с методом `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Сериализует данный экземпляр [`Argb32Color`](../argb32color) в шестнадцатеричную нотацию `##RRGGBB` как строку без альфа‑канала |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Сериализует данный экземпляр [`Argb32Color`](../argb32color) в шестнадцатеричную нотацию `##RRGGBBAA` как строку с альфа‑каналом |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Сериализует данный экземпляр [`Argb32Color`](../argb32color) в CSS‑функцию 'rgb'. Альфа‑канал этого цвета будет опущен при сериализации. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Сериализует данный экземпляр [`Argb32Color`](../argb32color) в CSS‑функцию 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Сериализует данный экземпляр [`Argb32Color`](../argb32color) в наиболее подходящую CSS‑функцию в зависимости от полупрозрачности |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Сравнивает два цвета [`Argb32Color`](../argb32color) и возвращает логическое значение, указывающее, совпадают ли они. (2 оператора) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Явно преобразует 32‑битный [`Argb32Color`](../argb32color) в 24‑битный [`Rgb24Color`](../rgb24color). Альфа‑канал исходного [`Argb32Color`](../argb32color) будет потерян после преобразования, поскольку [`Rgb24Color`](../rgb24color) не поддерживает прозрачность. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Неявно преобразует 24‑битный [`Rgb24Color`](../rgb24color) в 32‑битный [`Argb32Color`](../argb32color). Альфа‑канал результирующего [`Argb32Color`](../argb32color) будет установлен в `255` — полностью непрозрачный. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Сравнивает два цвета [`Argb32Color`](../argb32color) и возвращает логическое значение, указывающее, не совпадают ли они. (2 оператора) |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Возвращает пустой цвет, у которого нет информации о каналах и который полностью прозрачен. То же, что '[`Transparent`](./transparent)'. Значение по умолчанию. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Полностью прозрачный пустой цвет. То же, что значение цвета по умолчанию '[`Empty`](./empty)'. |

### Примечания

Этот тип предназначен для использования в (но не ограничивается) операциях CSS. Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### См. также

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
