---
title: "Rgb24Color"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa un color de 24 bits en formato RGB con 8 bits por cada canal Rojo Verde Azul. No admite transparencia."
type: docs
weight: 970
url: /es/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

Representa color de 24 bits en formato RGB, con 8 bits por cada canal (Rojo, Verde, Azul). No soporta transparencia.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | Obtiene la parte azul del color como entero sin signo de 8 bits [0..255] |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | Obtiene la parte verde del color como entero sin signo de 8 bits [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | Indica si esta instancia de [`Rgb24Color`](../rgb24color) es la predeterminada (Negro) - los 3 canales están establecidos en 0. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | Obtiene la parte roja del color como entero sin signo de 8 bits [0..255] |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | Crea un valor de [`Rgb24Color`](../rgb24color) a partir de los canales Rojo, Verde y Azul especificados |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | Comprueba si este color es igual al color [`Argb32Color`](../argb32color) especificado |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | Comprueba este color con el especificado sin convertir |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | Comprueba si este color es igual al color [`Rgb24Color`](../rgb24color) especificado |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | Devuelve la luminosidad/brillo Hue-Saturation-Lightness (HSL) para esta instancia de [`Rgb24Color`](../rgb24color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | Devuelve un código hash que define el color actual. No compatible con GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | Devuelve el valor de matiz Hue-Saturation-Lightness (HSL), en grados, para esta instancia de [`Rgb24Color`](../rgb24color). Si R == G == B, el matiz no tiene sentido, y el valor devuelto es 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | La saturación Hue-Saturation-Lightness (HSL) para esta instancia de [`Rgb24Color`](../rgb24color) |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | Devuelve el valor ARGB de esta instancia de [`Rgb24Color`](../rgb24color), compatible con Color |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | Devuelve este color en representación de cadena hexadecimal |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | Serializa esta instancia de [`Rgb24Color`](../rgb24color) a la notación de función CSS 'rgb'. |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | Serializa esta instancia de [`Rgb24Color`](../rgb24color) al formato 'rgb(r, g, b)' |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | Compara dos colores [`Rgb24Color`](../rgb24color) y devuelve un booleano que indica si los dos coinciden. (2 operadores) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | Compara dos colores [`Rgb24Color`](../rgb24color) y devuelve un booleano que indica si los dos no coinciden. (2 operadores) |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | Contiene todos los "colores conocidos", que tienen un nombre y valor único y fijo en el estándar CSS |

### Observaciones

Este tipo está diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ver también

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
