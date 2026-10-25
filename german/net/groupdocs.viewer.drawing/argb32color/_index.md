---
title: "Argb32Color"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt eine 32‑Bit‑Farbe im ARGB‑Format dar, mit 8 Bit pro Kanal (Alpha, Rot, Grün, Blau). Unterstützt Transparenz."
type: docs
weight: 950
url: /de/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Stellt 32‑Bit‑Farbe im ARGB‑Format dar, mit 8 Bits pro Kanal (Alpha, Rot, Grün, Blau). Unterstützt Transparenz.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Gibt den Alpha‑Teil der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl zurück [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Gibt den Alpha‑Anteil der Farbe in Prozent im Bereich (0..1) zurück. |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Gibt den Blauanteil der Farbe als 8‑Bit‑Unsigned‑Integer [0..255] zurück. |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Gibt den Grünanteil der Farbe als 8‑Bit‑Unsigned‑Integer [0..255] zurück. |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Gibt an, ob diese [`Argb32Color`](../argb32color)-Instanz standardmäßig (Transparent) ist – alle 4 Kanäle sind auf 0 gesetzt. Entspricht [`IsEmpty`](./isempty). |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Gibt an, ob diese [`Argb32Color`](../argb32color)-Farbinstanz nicht initialisiert ist – alle 4 Kanäle sind auf 0 gesetzt. Entspricht Standard und Transparent. Entspricht [`IsDefault`](./isdefault). |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Gibt an, ob diese [`Argb32Color`](../argb32color)-Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha‑Kanal hat den Maximalwert). |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Gibt an, ob diese [`Argb32Color`](../argb32color)-Instanz vollständig transparent ist – ihr Alpha‑Kanal hat den Minimalwert (0), sodass die anderen R‑, G‑ und B‑Kanäle keine sichtbare Wirkung haben. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Gibt an, ob diese [`Argb32Color`](../argb32color)-Instanz transluzent ist (weder vollständig transparent noch vollständig undurchsichtig). |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Gibt den Rotanteil der Farbe als 8‑Bit‑Unsigned‑Integer [0..255] zurück. |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Gibt den Int32‑Wert der Farbe als 32‑Bit‑Signed‑Integer zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Erstellt eine [`Argb32Color`](../argb32color)-Instanz aus ihren 32‑Bit‑Komponenten (Alpha, Rot, Grün und Blau), kompatibel mit dem von der Methode `System.Drawing.Color.ToArgb()` erzeugten Wert. |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Erstellt eine neue [`Argb32Color`](../argb32color)-Instanz aus den angegebenen Werten, jedoch mit neu definiertem Alpha‑ (Opazitäts‑) Wert. |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Erstellt eine neue [`Argb32Color`](../argb32color)-Instanz aus dem angegebenen [`Rgb24Color`](../rgb24color), jedoch mit dem angegebenen Alpha‑ (Opazitäts‑) Wert. |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Erstellt einen [`Argb32Color`](../argb32color)-Wert aus den angegebenen Rot‑, Grün‑ und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig ist. |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Erstellt einen [`Argb32Color`](../argb32color)-Wert aus den angegebenen Rot‑, Grün‑, Blau‑ und Alpha‑Kanälen. |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Wert, der auf alle Kanäle angewendet wird. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Prüft diese Farbe auf Gleichheit mit der angegebenen [`Argb32Color`](../argb32color)-Farbe. |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Prüft diese Farbe mit dem angegebenen nicht gecasteten Wert. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Prüft diese Farbe auf Gleichheit mit der angegebenen [`Rgb24Color`](../rgb24color)-Farbe. |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Gibt die Helligkeit (Lightness) des Hue‑Saturation‑Lightness (HSL)-Modells für diese [`Argb32Color`](../argb32color)-Instanz zurück. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Gibt einen Hash‑Code zurück, der die aktuelle Farbe definiert. Nicht kompatibel mit GetHashCode. |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Gibt den Farbtonwert (Hue) des Hue‑Saturation‑Lightness (HSL)-Modells in Grad für diese [`Argb32Color`](../argb32color)-Instanz zurück. Wenn R == G == B, ist der Farbton bedeutungslos und der Rückgabewert ist 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | Die Sättigung des Hue‑Saturation‑Lightness (HSL)-Modells für diese [`Argb32Color`](../argb32color)-Instanz. |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Gibt den ARGB‑Wert dieser [`Argb32Color`](../argb32color)-Instanz zurück, kompatibel mit der Methode `System.Drawing.Color.ToArgb()`. |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Serialisiert diese [`Argb32Color`](../argb32color)-Instanz in die hexadezimale Notation `##RRGGBB` als Zeichenkette ohne Alpha‑Kanal. |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Serialisiert diese [`Argb32Color`](../argb32color)-Instanz in die hexadezimale Notation `##RRGGBBAA` als Zeichenkette mit Alphakanal |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Serialisiert diese [`Argb32Color`](../argb32color)-Instanz in die CSS‑Funktionsnotation 'rgb'. Der Alphakanal dieser Farbe wird bei der Serialisierung weggelassen. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Serialisiert diese [`Argb32Color`](../argb32color)-Instanz in die CSS‑Funktionsnotation 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Serialisiert diese [`Argb32Color`](../argb32color)-Instanz in die am besten geeignete CSS‑Funktionsnotation, abhängig von der Transparenz |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Vergleicht zwei [`Argb32Color`](../argb32color)-Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. (2 Operatoren) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Wandelt explizit die 32‑Bit-[`Argb32Color`](../argb32color) in die 24‑Bit-[`Rgb24Color`](../rgb24color) um. Der Alphakanal der Quell-[`Argb32Color`](../argb32color) geht beim Casten verloren, weil [`Rgb24Color`](../rgb24color) keine Transparenz unterstützt. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Wandelt implizit die 24‑Bit-[`Rgb24Color`](../rgb24color) in die 32‑Bit-[`Argb32Color`](../argb32color) um. Der Alphakanal der Ausgabe-[`Argb32Color`](../argb32color) wird auf `255` gesetzt – vollständig undurchsichtig. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Vergleicht zwei [`Argb32Color`](../argb32color)-Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht übereinstimmen. (2 Operatoren) |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Gibt eine leere Farbe zurück, die keine Kanalinformationen enthält und vollständig transparent ist. Gleich wie '[`Transparent`](./transparent)'. Standardwert. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Vollständig transparente leere Farbe. Das gleiche wie der Standardwert der Farbe '[`Empty`](./empty)'. |

### Bemerkungen

Dieser Typ ist dafür ausgelegt, für (aber nicht ausschließlich) CSS‑Operationen nützlich zu sein. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Siehe auch

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
