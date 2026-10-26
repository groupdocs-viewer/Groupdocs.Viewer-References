---
title: "Rgb24Color"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет 24‑битный цвет в формате RGB с 8 битами на каждый канал Red, Green, Blue. Не поддерживает прозрачность."
type: docs
weight: 970
url: /ru/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

Представляет 24‑битный цвет в формате RGB, с 8 битами на каждый канал (Red, Green, Blue). Не поддерживает прозрачность.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | Получает синюю часть цвета как 8‑битное беззнаковое целое [0..255] |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | Получает зелёную часть цвета как 8‑битное беззнаковое целое [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | Указывает, является ли данный экземпляр [`Rgb24Color`](../rgb24color) значением по умолчанию (Black) — все 3 канала установлены в 0. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | Возвращает красную часть цвета как 8‑битное беззнаковое целое [0..255] |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | Создаёт одно значение [`Rgb24Color`](../rgb24color) из указанных каналов Red, Green, Blue. |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | Проверяет равенство этого цвета с указанным цветом [`Argb32Color`](../argb32color) |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | Проверяет этот цвет с указанным неконвертированным |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | Проверяет равенство этого цвета с указанным цветом [`Rgb24Color`](../rgb24color) |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | Возвращает светлоту/яркость Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Rgb24Color`](../rgb24color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | Возвращает хеш‑код, определяющий текущий цвет. Не совместим с GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | Возвращает значение оттенка Hue-Saturation-Lightness (HSL) в градусах для данного экземпляра [`Rgb24Color`](../rgb24color). Если R == G == B, оттенок не имеет смысла, и возвращаемое значение равно 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | Насыщенность Hue-Saturation-Lightness (HSL) для данного экземпляра [`Rgb24Color`](../rgb24color). |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | Возвращает значение ARGB данного экземпляра [`Rgb24Color`](../rgb24color), совместимое с Color. |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | Возвращает этот цвет в виде шестнадцатеричной строковой репрезентации. |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | Сериализует данный экземпляр [`Rgb24Color`](../rgb24color) в нотацию CSS функции 'rgb'. |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | Сериализует данный экземпляр [`Rgb24Color`](../rgb24color) в формат 'rgb(r, g, b)'. |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | Сравнивает два цвета [`Rgb24Color`](../rgb24color) и возвращает логическое значение, указывающее, совпадают ли они. (2 оператора) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | Сравнивает два цвета [`Rgb24Color`](../rgb24color) и возвращает логическое значение, указывающее, не совпадают ли они. (2 оператора) |

## Другие члены

| Имя | Описание |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | Содержит все "известные цвета", которые имеют фиксированное уникальное имя и значение в стандарте CSS. |

### Примечания

Этот тип предназначен для использования в (но не ограничивается) операциях CSS. Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### См. также

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
