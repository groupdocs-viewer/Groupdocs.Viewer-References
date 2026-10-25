---
title: "Argb32Color"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente une couleur 32 bits au format ARGB avec 8 bits par canal Alpha Rouge Vert Bleu. Prend en charge la transparence."
type: docs
weight: 950
url: /fr/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Représente une couleur 32 bits au format ARGB, avec 8 bits par canal (Alpha, Rouge, Vert, Bleu). Prend en charge la transparence.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Obtient la partie alpha de la couleur sous forme d'entier non signé de 8 bits [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Obtient la partie alpha de la couleur en pourcentage dans la plage (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Obtient la partie bleue de la couleur sous forme d'entier non signé de 8 bits [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Obtient la partie verte de la couleur sous forme d'entier non signé de 8 bits [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Indique si cette instance [`Argb32Color`](../argb32color) est par défaut (Transparent) - les 4 canaux sont à 0. Identique à [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Indique si cette instance de couleur [`Argb32Color`](../argb32color) est non initialisée - les 4 canaux sont à 0. Identique à Par défaut et Transparent. Identique à [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Indique si cette instance [`Argb32Color`](../argb32color) est totalement opaque, sans transparence (son canal Alpha a la valeur maximale) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Indique si cette instance [`Argb32Color`](../argb32color) est totalement transparente - son canal Alpha a la valeur minimale (0), de sorte que les autres canaux R, G et B n'ont aucun effet visible. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Indique si cette instance de [`Argb32Color`](../argb32color) est translucide (pas complètement transparente, mais pas non plus complètement opaque) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Obtient la partie rouge de la couleur sous forme d'entier non signé de 8 bits [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Obtient la valeur Int32 de la couleur sous forme d'entier signé de 32 bits |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Crée une instance de [`Argb32Color`](../argb32color) à partir de ses composants 32 bits (alpha, rouge, vert et bleu), compatible avec la valeur produite par la méthode `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Crée une nouvelle instance de [`Argb32Color`](../argb32color) à partir de la couleur spécifiée, mais avec une valeur alpha (opacité) redéfinie |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Crée une nouvelle instance de [`Argb32Color`](../argb32color) à partir d'un [`Rgb24Color`](../rgb24color) spécifié, mais avec une valeur alpha (opacité) spécifiée |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Crée une valeur de [`Argb32Color`](../argb32color) à partir des canaux Rouge, Vert, Bleu spécifiés, tandis que le canal Alpha est entièrement opaque |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Crée une valeur de [`Argb32Color`](../argb32color) à partir des canaux Rouge, Vert, Bleu et Alpha spécifiés |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Crée une couleur entièrement opaque (A=255) à partir d'une valeur unique, qui sera appliquée à tous les canaux |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Vérifie l'égalité de cette couleur avec la couleur [`Argb32Color`](../argb32color) spécifiée |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Vérifie cette couleur avec la couleur non convertie spécifiée |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Vérifie l'égalité de cette couleur avec la couleur [`Rgb24Color`](../rgb24color) spécifiée |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Renvoie la luminosité (lightness) de la teinte-saturation-luminosité (HSL) pour cette instance de [`Argb32Color`](../argb32color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Renvoie un code de hachage qui définit la couleur actuelle. Non compatible avec GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Renvoie la valeur de teinte (hue) de la teinte-saturation-luminosité (HSL), en degrés, pour cette instance de [`Argb32Color`](../argb32color). Si R == G == B, la teinte n'a aucun sens, et la valeur renvoyée est 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | La saturation de la teinte-saturation-luminosité (HSL) pour cette instance de [`Argb32Color`](../argb32color) |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Renvoie la valeur ARGB de cette instance de [`Argb32Color`](../argb32color), compatible avec la méthode `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Sérialise cette instance de [`Argb32Color`](../argb32color) en notation hexadécimale `##RRGGBB` sous forme de chaîne sans canal alpha |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Sérialise cette instance de [`Argb32Color`](../argb32color) en notation hexadécimale `##RRGGBBAA` sous forme de chaîne avec canal alpha |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Sérialise cette instance de [`Argb32Color`](../argb32color) en notation de fonction CSS 'rgb'. Le canal alpha de cette couleur sera omis lors de la sérialisation. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Sérialise cette instance de [`Argb32Color`](../argb32color) en notation de fonction CSS 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Sérialise cette instance de [`Argb32Color`](../argb32color) en la notation de fonction CSS la plus appropriée selon la translucidité |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Compare deux couleurs [`Argb32Color`](../argb32color) et renvoie un booléen indiquant si les deux correspondent. (2 opérateurs) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Convertit explicitement le [`Argb32Color`](../argb32color) 32 bits en [`Rgb24Color`](../rgb24color) 24 bits. Le canal alpha du [`Argb32Color`](../argb32color) source sera perdu après la conversion, car le [`Rgb24Color`](../rgb24color) ne prend pas en charge la transparence. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Convertit implicitement le [`Rgb24Color`](../rgb24color) 24 bits en [`Argb32Color`](../argb32color) 32 bits. Le canal alpha du [`Argb32Color`](../argb32color) de sortie sera réglé à `255` - entièrement opaque. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Compare deux couleurs [`Argb32Color`](../argb32color) et renvoie un booléen indiquant si les deux ne correspondent pas. (2 opérateurs) |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Renvoie une couleur vide, qui n’a aucune information de canaux et est totalement transparente. Identique à '[`Transparent`](./transparent)'. Valeur par défaut. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Couleur vide totalement transparente. Identique à la valeur de couleur par défaut '[`Empty`](./empty)'. |

### Remarques

Ce type est conçu pour être utile aux opérations CSS (mais pas uniquement). Voir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Voir aussi

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
