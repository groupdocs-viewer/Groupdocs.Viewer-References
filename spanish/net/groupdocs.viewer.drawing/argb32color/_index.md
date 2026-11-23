---
title: "Argb32Color"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa un color de 32 bits en formato ARGB con 8 bits por cada canal Alfa Rojo Verde Azul. Soporta transparencia."
type: docs
weight: 950
url: /es/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Representa color de 32 bits en formato ARGB, con 8 bits por cada canal (Alfa, Rojo, Verde, Azul). Soporta transparencia.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Obtiene la parte alfa del color como entero sin signo de 8 bits [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Obtiene la parte alfa del color en porcentaje en el rango (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Obtiene la parte azul del color como entero sin signo de 8 bits [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Obtiene la parte verde del color como entero sin signo de 8 bits [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Indica si esta instancia de [`Argb32Color`](../argb32color) es predeterminada (Transparente) - los 4 canales están configurados a 0. Igual que [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Indica si esta instancia de color [`Argb32Color`](../argb32color) no está inicializada - los 4 canales están configurados a 0. Igual que Predeterminado y Transparente. Igual que [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Indica si esta instancia de [`Argb32Color`](../argb32color) es completamente opaca, sin transparencia (su canal Alfa tiene el valor máximo) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Indica si esta instancia de [`Argb32Color`](../argb32color) es completamente transparente - su canal Alfa tiene el valor mínimo (0), por lo que los demás canales R, G y B no tienen efecto visible. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Indica si esta instancia de [`Argb32Color`](../argb32color) es translúcida (no completamente transparente, pero tampoco completamente opaca) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Obtiene la parte roja del color como entero sin signo de 8 bits [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Obtiene el valor Int32 del color como entero con signo de 32 bits |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Crea una instancia de [`Argb32Color`](../argb32color) a partir de sus componentes de 32 bits (alfa, rojo, verde y azul), compatible con el valor producido por el método `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Crea una nueva instancia de [`Argb32Color`](../argb32color) a partir de los especificados, pero con un valor alfa (opacidad) redefinido |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Crea una nueva instancia de [`Argb32Color`](../argb32color) a partir del [`Rgb24Color`](../rgb24color) especificado, pero con el valor alfa (opacidad) especificado |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Crea un valor de [`Argb32Color`](../argb32color) a partir de los canales Rojo, Verde y Azul especificados, mientras que el canal Alfa es totalmente opaco |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Crea un valor de [`Argb32Color`](../argb32color) a partir de los canales Rojo, Verde, Azul y Alfa especificados |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Crea un color totalmente opaco (A=255) a partir de un único valor, que se aplicará a todos los canales |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Comprueba si este color es igual al color [`Argb32Color`](../argb32color) especificado |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Comprueba este color con el especificado sin convertir |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Comprueba si este color es igual al color [`Rgb24Color`](../rgb24color) especificado |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Devuelve la luminosidad/brillo Hue-Saturation-Lightness (HSL) de esta instancia de [`Argb32Color`](../argb32color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Devuelve un código hash que define el color actual. No compatible con GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Devuelve el valor de tono Hue-Saturation-Lightness (HSL), en grados, de esta instancia de [`Argb32Color`](../argb32color). Si R == G == B, el tono no tiene sentido y el valor devuelto es 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | La saturación Hue-Saturation-Lightness (HSL) de esta instancia de [`Argb32Color`](../argb32color) |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Devuelve el valor ARGB de esta instancia de [`Argb32Color`](../argb32color), compatible con el método `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Serializa esta instancia de [`Argb32Color`](../argb32color) a la notación hexadecimal `##RRGGBB` como una cadena sin canal alfa |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Serializa esta instancia de [`Argb32Color`](../argb32color) a la notación hexadecimal `##RRGGBBAA` como una cadena con canal alfa |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Serializa esta instancia de [`Argb32Color`](../argb32color) a la notación de función CSS 'rgb'. El canal alfa de este color se omitirá durante la serialización. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Serializa esta instancia de [`Argb32Color`](../argb32color) a la notación de función CSS 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Serializa esta instancia de [`Argb32Color`](../argb32color) a la notación de función CSS más adecuada según la translucidez |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Compara dos colores [`Argb32Color`](../argb32color) y devuelve un booleano que indica si coinciden. (2 operadores) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Convierte explícitamente el [`Argb32Color`](../argb32color) de 32 bits a [`Rgb24Color`](../rgb24color) de 24 bits. El canal alfa del [`Argb32Color`](../argb32color) de origen se perderá después de la conversión, porque [`Rgb24Color`](../rgb24color) no admite transparencia. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Convierte implícitamente el [`Rgb24Color`](../rgb24color) de 24 bits a [`Argb32Color`](../argb32color) de 32 bits. El canal alfa del [`Argb32Color`](../argb32color) de salida se establecerá en `255`, totalmente opaco. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Compara dos colores [`Argb32Color`](../argb32color) y devuelve un booleano que indica si los dos no coinciden. (2 operadores) |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Devuelve un color vacío, que no tiene información de canales y es totalmente transparente. Igual que '[`Transparent`](./transparent)'. Valor predeterminado. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Color vacío totalmente transparente. Igual que el valor predeterminado del color '[`Empty`](./empty)'. |

### Observaciones

Este tipo está diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ver también

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
