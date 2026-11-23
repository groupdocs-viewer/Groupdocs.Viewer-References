---
title: "Argb32Color"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Stelt een 32‑bit kleur voor in ARGB‑formaat met 8 bits per elk kanaal Alpha Rood Groen Blauw. Ondersteunt transparantie."
type: docs
weight: 950
url: /nl/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Stelt een 32-bits kleur in ARGB-formaat voor, met 8 bits per elk kanaal (Alpha, Rood, Groen, Blauw). Ondersteunt transparantie.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Haalt het alfa‑gedeelte van de kleur op als 8‑bit ongetekend geheel getal [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Haalt het alfa‑gedeelte van de kleur op in procenten in het bereik (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Haalt het blauwe gedeelte van de kleur op als 8‑bit ongetekend geheel getal [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Haalt het groene gedeelte van de kleur op als 8‑bit ongetekend geheel getal [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Geeft aan of deze [`Argb32Color`](../argb32color) instantie standaard (Transparant) is - alle 4 kanalen zijn ingesteld op 0. Hetzelfde als [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Geeft aan of deze [`Argb32Color`](../argb32color) kleurinstantie niet geïnitialiseerd is - alle 4 kanalen zijn ingesteld op 0. Hetzelfde als Standaard en Transparant. Hetzelfde als [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Geeft aan of deze [`Argb32Color`](../argb32color) instantie volledig ondoorzichtig is, zonder transparantie (het Alpha‑kanaal heeft maximale waarde) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Geeft aan of deze [`Argb32Color`](../argb32color) instantie volledig transparant is - het Alpha‑kanaal heeft de minimale (0) waarde, waardoor de andere R-, G- en B‑kanalen geen zichtbaar effect hebben. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Geeft aan of deze [`Argb32Color`](../argb32color) instantie doorschijnend is (niet volledig transparant, maar ook niet volledig ondoorzichtig) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Haalt het rode gedeelte van de kleur op als 8-bit unsigned integer [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Haalt de Int32-waarde van de kleur op als 32-bit signed integer |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Maakt een [`Argb32Color`](../argb32color) instantie aan vanuit zijn 32-bit component (alpha, rood, groen en blauw) waarden, compatibel met de waarde die wordt geproduceerd door de `System.Drawing.Color.ToArgb()` methode |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Maakt een nieuwe [`Argb32Color`](../argb32color) instantie aan vanuit gespecificeerde waarden, maar met opnieuw gedefinieerde alpha (opaciteit) waarde |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Maakt een nieuwe [`Argb32Color`](../argb32color) instantie aan vanuit gespecificeerde [`Rgb24Color`](../rgb24color), maar met een gespecificeerde alpha (opaciteit) waarde |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Creëert één [`Argb32Color`](../argb32color) waarde uit gespecificeerde rood-, groen- en blauwkanalen, terwijl het alpha-kanaal volledig ondoorzichtig is |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Creëert één [`Argb32Color`](../argb32color) waarde uit gespecificeerde rood-, groen-, blauw- en alpha-kanalen |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Maakt een volledig ondoorzichtige (A=255) kleur aan vanuit één waarde, die op alle kanalen wordt toegepast |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Controleert deze kleur met de gespecificeerde [`Argb32Color`](../argb32color) kleur op gelijkheid |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Controleert deze kleur met de gespecificeerde niet-gecastte |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Controleert deze kleur met de gespecificeerde [`Rgb24Color`](../rgb24color) kleur op gelijkheid |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Retourneert de Hue-Saturation-Lightness (HSL) lichtheid/helderheid voor deze [`Argb32Color`](../argb32color) instantie. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Retourneert een hashcode die de huidige kleur definieert. Niet compatibel met GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Retourneert de Hue-Saturation-Lightness (HSL) tintwaarde, in graden, voor deze [`Argb32Color`](../argb32color) instantie. Als R == G == B, is de tint betekenisloos, en is de geretourneerde waarde 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | De Hue-Saturation-Lightness (HSL) verzadiging voor deze [`Argb32Color`](../argb32color) instantie |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Retourneert de ARGB-waarde van deze [`Argb32Color`](../argb32color) instantie, compatibel met de `System.Drawing.Color.ToArgb()` methode |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Serialiseert deze [`Argb32Color`](../argb32color) instantie naar de hexadecimale notatie `##RRGGBB` als een string zonder alpha-kanaal |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Serialiseert deze [`Argb32Color`](../argb32color) instantie naar de hexadecimale notatie `##RRGGBBAA` als een string met alpha-kanaal |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Serialiseert deze [`Argb32Color`](../argb32color) instantie naar de 'rgb' CSS-functienotatie. Het alpha-kanaal van deze kleur wordt weggelaten tijdens serialisatie. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Serialiseert deze [`Argb32Color`](../argb32color) instantie naar de 'rgba' CSS-functienotatie |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Serialiseert deze [`Argb32Color`](../argb32color) instantie naar de meest geschikte CSS-functienotatie afhankelijk van doorschijnendheid |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Vergelijkt twee [`Argb32Color`](../argb32color) kleuren en retourneert een boolean die aangeeft of de twee overeenkomen. (2 operatoren) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Cast expliciet de 32-bit [`Argb32Color`](../argb32color) naar 24-bit [`Rgb24Color`](../rgb24color). Het alpha-kanaal van de bron [`Argb32Color`](../argb32color) gaat verloren na het casten, omdat [`Rgb24Color`](../rgb24color) geen transparantie ondersteunt. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Cast impliciet de 24-bit [`Rgb24Color`](../rgb24color) naar 32-bit [`Argb32Color`](../argb32color). Het alpha-kanaal van de uitvoer [`Argb32Color`](../argb32color) wordt ingesteld op `255` - volledig ondoorzichtig. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Vergelijkt twee [`Argb32Color`](../argb32color)-kleuren en retourneert een boolean die aangeeft of de twee niet overeenkomen. (2 operatoren) |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Retourneert een lege kleur, die geen kanaalinformatie heeft en volledig transparant is. Hetzelfde als '[`Transparent`](./transparent)'. Standaardwaarde. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Volledig transparante lege kleur. Hetzelfde als de standaard '[`Empty`](./empty)'-kleurwaarde. |

### Opmerkingen

Dit type is ontworpen om nuttig te zijn voor (maar niet beperkt tot) CSS-bewerkingen. Zie meer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Zie ook

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
