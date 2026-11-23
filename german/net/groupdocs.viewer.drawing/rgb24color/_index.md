---
title: "Rgb24Color"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt eine 24‑Bit‑Farbe im RGB‑Format dar, mit 8 Bit pro Kanal Rot, Grün und Blau. Unterstützt keine Transparenz."
type: docs
weight: 970
url: /de/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

Stellt 24‑Bit‑Farbe im RGB‑Format dar, mit 8 Bits pro Kanal (Rot, Grün, Blau). Unterstützt keine Transparenz.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | Gibt den Blauanteil der Farbe als 8‑Bit‑Unsigned‑Integer [0..255] zurück. |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | Gibt den Grünanteil der Farbe als 8‑Bit‑Unsigned‑Integer [0..255] zurück. |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | Gibt an, ob diese [`Rgb24Color`](../rgb24color)-Instanz Standard (Schwarz) ist – alle 3 Kanäle sind auf 0 gesetzt. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | Gibt den Rotanteil der Farbe als 8‑Bit‑Unsigned‑Integer [0..255] zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | Erstellt einen [`Rgb24Color`](../rgb24color)-Wert aus den angegebenen Rot‑, Grün‑ und Blau‑Kanälen |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | Prüft diese Farbe auf Gleichheit mit der angegebenen [`Argb32Color`](../argb32color)-Farbe. |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | Prüft diese Farbe mit dem angegebenen nicht gecasteten Wert. |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | Prüft diese Farbe auf Gleichheit mit der angegebenen [`Rgb24Color`](../rgb24color)-Farbe. |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | Gibt die Helligkeit (Lightness) des Hue‑Saturation‑Lightness (HSL)-Modells für diese [`Rgb24Color`](../rgb24color)-Instanz zurück. |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | Gibt einen Hash‑Code zurück, der die aktuelle Farbe definiert. Nicht kompatibel mit GetHashCode. |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | Gibt den Farbton (Hue) des Hue‑Saturation‑Lightness (HSL)-Modells in Grad für diese [`Rgb24Color`](../rgb24color)-Instanz zurück. Wenn R == G == B, ist der Farbton bedeutungslos und der Rückgabewert ist 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | Die Sättigung (Saturation) des Hue‑Saturation‑Lightness (HSL)-Modells für diese [`Rgb24Color`](../rgb24color)-Instanz |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | Gibt den ARGB‑Wert dieser [`Rgb24Color`](../rgb24color)-Instanz zurück, kompatibel mit Color |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | Gibt diese Farbe als hexadezimale Zeichenkette zurück |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | Serialisiert diese [`Rgb24Color`](../rgb24color)-Instanz in die CSS‑Funktionsschreibweise 'rgb'. |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | Serialisiert diese [`Rgb24Color`](../rgb24color)-Instanz in das Format 'rgb(r, g, b)' |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | Vergleicht zwei [`Rgb24Color`](../rgb24color)-Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. (2 Operatoren) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | Vergleicht zwei [`Rgb24Color`](../rgb24color)-Farben und gibt einen booleschen Wert zurück, der angibt, dass die beiden nicht übereinstimmen. (2 Operatoren) |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | Enthält alle "bekannten Farben", die einen festen eindeutigen Namen und Wert im CSS-Standard haben |

### Bemerkungen

Dieser Typ ist dafür ausgelegt, für (aber nicht ausschließlich) CSS‑Operationen nützlich zu sein. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Siehe auch

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
