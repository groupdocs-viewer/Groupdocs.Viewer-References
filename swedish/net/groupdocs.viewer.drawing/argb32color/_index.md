---
title: "Argb32Color"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Representerar 32‑bit färg i ARGB-format med 8 bitar per kanal för Alfa, Röd, Grön och Blå. Stöder transparens."
type: docs
weight: 950
url: /sv/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Representerar 32-bitars färg i ARGB-format, med 8 bitar per kanal (Alfa, Röd, Grön, Blå). Stöder transparens.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Hämtar alfadelen av färgen som ett 8‑bit osignerat heltal [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Hämtar alfadelen av färgen i procent i (0..1)-intervallet. |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Hämtar blådelen av färgen som ett 8‑bit osignerat heltal [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Hämtar gröndelen av färgen som ett 8‑bit osignerat heltal [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Anger om detta [`Argb32Color`](../argb32color)-instans är standard (Transparent) - alla 4 kanaler är satta till 0. Samma som [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Anger om detta [`Argb32Color`](../argb32color)-färginstans är oinitierad - alla 4 kanaler är satta till 0. Samma som Standard och Transparent. Samma som [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Anger om detta [`Argb32Color`](../argb32color)-instans är helt ogenomskinlig, utan transparens (dess Alpha-kanal har maximalt värde) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Anger om detta [`Argb32Color`](../argb32color)-instans är helt transparent - dess Alpha-kanal har det minsta (0) värdet, så de andra R-, G- och B-kanalerna har ingen synlig effekt. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Anger om detta [`Argb32Color`](../argb32color)-instans är genomskinlig (inte helt transparent, men inte heller helt ogenomskinlig) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Hämtar den röda delen av färgen som en 8-bitars osignerad heltal [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Hämtar Int32‑värdet för färgen som ett 32-bitars signerat heltal |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Skapar en [`Argb32Color`](../argb32color)-instans från dess 32-bitars komponenter (alpha, röd, grön och blå) värden, kompatibel med värdet som produceras av metoden `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Skapar en ny [`Argb32Color`](../argb32color)-instans från angivet, men med omdefinierat alfa‑värde (opacitet) |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Skapar en ny [`Argb32Color`](../argb32color)-instans från angiven [`Rgb24Color`](../rgb24color), men med angivet alfa‑värde (opacitet) |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Skapar ett [`Argb32Color`](../argb32color)-värde från angivna Röd-, Grön- och Blå-kanaler, medan Alfa-kanalen är helt ogenomskinlig |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Skapar ett [`Argb32Color`](../argb32color)-värde från angivna Röd-, Grön-, Blå- och Alfa-kanaler |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Skapar en helt ogenomskinlig (A=255) färg från ett enda värde, som kommer att tillämpas på alla kanaler |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Kontrollerar om denna färg är lika med den angivna [`Argb32Color`](../argb32color)-färgen |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Kontrollerar denna färg med angivet okastat värde |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Kontrollerar om denna färg är lika med den angivna [`Rgb24Color`](../rgb24color)-färgen |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Returnerar Hue‑Saturation‑Lightness‑ (HSL) ljushet för denna [`Argb32Color`](../argb32color)-instans. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Returnerar en hashkod som definierar den aktuella färgen. Inte kompatibel med GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Returnerar Hue‑Saturation‑Lightness‑ (HSL) nyansvärde i grader för denna [`Argb32Color`](../argb32color)-instans. Om R == G == B är nyansen meningslös och returvärdet är 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | Hue‑Saturation‑Lightness‑ (HSL) mättnad för denna [`Argb32Color`](../argb32color)-instans |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Returnerar ARGB‑värdet för denna [`Argb32Color`](../argb32color)-instans, kompatibelt med metoden `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Serialiserar denna [`Argb32Color`](../argb32color)-instans till den hexadecimala notationen `##RRGGBB` som en sträng utan alfa‑kanal |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Serialiserar denna [`Argb32Color`](../argb32color)-instans till den hexadecimala notationen `##RRGGBBAA` som en sträng med alfa‑kanal |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Serialiserar denna [`Argb32Color`](../argb32color)-instans till CSS-funktionsnotationen 'rgb'. Alfa‑kanalen för denna färg kommer att utelämnas vid serialisering. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Serialiserar denna [`Argb32Color`](../argb32color)-instans till CSS-funktionsnotationen 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Serialiserar detta [`Argb32Color`](../argb32color) instans till den mest lämpliga CSS-funktionsnotationen beroende på genomskinlighet. |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Jämför två [`Argb32Color`](../argb32color)-färger och returnerar ett booleskt värde som indikerar om de två matchar. (2 operatorer) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Kastar uttryckligen den 32-bitars [`Argb32Color`](../argb32color) till 24-bitars [`Rgb24Color`](../rgb24color). Alfa-kanalen i käll‑[`Argb32Color`](../argb32color) kommer att gå förlorad efter kastet, eftersom [`Rgb24Color`](../rgb24color) inte stödjer transparens. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Kastar implicit den 24-bitars [`Rgb24Color`](../rgb24color) till 32-bitars [`Argb32Color`](../argb32color). Alfa-kanalen i utdata‑[`Argb32Color`](../argb32color) kommer att sättas till `255` – helt ogenomskinlig. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Jämför två [`Argb32Color`](../argb32color)-färger och returnerar ett booleskt värde som indikerar om de två inte matchar. (2 operatorer) |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Returnerar en tom färg, som saknar kanalinformation och är helt genomskinlig. Samma som '[`Transparent`](./transparent)'. Standardvärde. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Fullt genomskinlig tom färg. Samma som standardvärdet '[`Empty`](./empty)' färgvärde. |

### Anmärkningar

Denna typ är avsedd att vara användbar för (men inte begränsad till) CSS‑operationer. Se mer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Se även

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
