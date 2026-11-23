---
title: "Argb32Color"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Rappresenta un colore a 32 bit in formato ARGB con 8 bit per ogni canale Alpha Rosso Verde Blu. Supporta la trasparenza."
type: docs
weight: 950
url: /it/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Rappresenta un colore a 32 bit in formato ARGB, con 8 bit per ogni canale (Alpha, Rosso, Verde, Blu). Supporta la trasparenza.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Restituisce la parte alfa del colore come intero senza segno a 8 bit [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Restituisce la parte alfa del colore in percentuale nell'intervallo (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Restituisce la parte blu del colore come intero senza segno a 8 bit [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Restituisce la parte verde del colore come intero senza segno a 8 bit [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Indica se questa istanza di [`Argb32Color`](../argb32color) è predefinita (Trasparente) - tutti i 4 canali sono impostati a 0. Equivalente a [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Indica se questa istanza di colore [`Argb32Color`](../argb32color) non è inizializzata - tutti i 4 canali sono impostati a 0. Equivalente a Predefinito e Trasparente. Equivalente a [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Indica se questa istanza di [`Argb32Color`](../argb32color) è completamente opaca, senza trasparenza (il suo canale Alpha ha valore massimo) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Indica se questa istanza di [`Argb32Color`](../argb32color) è completamente trasparente - il suo canale Alpha ha il valore minimo (0), quindi gli altri canali R, G e B non hanno alcun effetto visibile. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Indica se questa istanza di [`Argb32Color`](../argb32color) è traslucida (non completamente trasparente, ma neanche completamente opaca) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Restituisce la parte rossa del colore come intero senza segno a 8 bit [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Restituisce il valore Int32 del colore come intero con segno a 32 bit |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Crea un'istanza di [`Argb32Color`](../argb32color) dai suoi componenti a 32 bit (alpha, rosso, verde e blu), compatibile con il valore prodotto dal metodo `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Crea una nuova istanza di [`Argb32Color`](../argb32color) da quella specificata, ma con valore alpha (opacità) ridefinito |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Crea una nuova istanza di [`Argb32Color`](../argb32color) da un [`Rgb24Color`](../rgb24color) specificato, ma con valore alpha (opacità) specificato |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Crea un valore di [`Argb32Color`](../argb32color) dai canali Rosso, Verde e Blu specificati, mentre il canale Alpha è completamente opaco |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Crea un valore di [`Argb32Color`](../argb32color) dai canali Rosso, Verde, Blu e Alpha specificati |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Crea un colore completamente opaco (A=255) da un singolo valore, che verrà applicato a tutti i canali |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Verifica se questo colore è uguale al colore [`Argb32Color`](../argb32color) specificato |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Verifica questo colore con quello specificato non convertito |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Verifica se questo colore è uguale al colore [`Rgb24Color`](../rgb24color) specificato |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Restituisce la luminosità (lightness) Hue-Saturation-Lightness (HSL) di questa istanza di [`Argb32Color`](../argb32color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Restituisce un codice hash che definisce il colore corrente. Non compatibile con GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Restituisce il valore di tonalità (hue) Hue-Saturation-Lightness (HSL), in gradi, per questa istanza di [`Argb32Color`](../argb32color). Se R == G == B, la tonalità è priva di significato e il valore restituito è 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | La saturazione Hue-Saturation-Lightness (HSL) per questa istanza di [`Argb32Color`](../argb32color) |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Restituisce il valore ARGB di questa istanza di [`Argb32Color`](../argb32color), compatibile con il metodo `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Serializza questa istanza di [`Argb32Color`](../argb32color) nella notazione esadecimale `##RRGGBB` come stringa senza canale alpha |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Serializza questa istanza di [`Argb32Color`](../argb32color) nella notazione esadecimale `##RRGGBBAA` come stringa con canale alpha |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Serializza questa istanza di [`Argb32Color`](../argb32color) nella notazione della funzione CSS 'rgb'. Il canale alpha di questo colore verrà omesso durante la serializzazione. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Serializza questa istanza di [`Argb32Color`](../argb32color) nella notazione della funzione CSS 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Serializza questa istanza di [`Argb32Color`](../argb32color) nella notazione della funzione CSS più appropriata in base alla traslucenza |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Confronta due colori [`Argb32Color`](../argb32color) e restituisce un valore booleano che indica se i due corrispondono. (2 operatori) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Esegue un cast esplicito del [`Argb32Color`](../argb32color) a 32 bit verso un [`Rgb24Color`](../rgb24color) a 24 bit. Il canale alpha del [`Argb32Color`](../argb32color) di origine verrà perso dopo il cast, poiché [`Rgb24Color`](../rgb24color) non supporta la trasparenza. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Esegue un cast implicito del [`Rgb24Color`](../rgb24color) a 24 bit verso un [`Argb32Color`](../argb32color) a 32 bit. Il canale alpha dell'[`Argb32Color`](../argb32color) di output verrà impostato a `255` - completamente opaco. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Confronta due colori [`Argb32Color`](../argb32color) e restituisce un booleano che indica se i due non corrispondono. (2 operatori) |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Restituisce un colore vuoto, che non ha informazioni sui canali ed è completamente trasparente. Identico a '[`Transparent`](./transparent)'. Valore predefinito. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Colore vuoto completamente trasparente. Identico al valore di colore predefinito '[`Empty`](./empty)'. |

### Osservazioni

Questo tipo è progettato per essere utile per (ma non limitato a) operazioni CSS. Vedi di più: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Vedi anche

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
