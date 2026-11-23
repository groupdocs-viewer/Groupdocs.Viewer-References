---
title: "Rgb24Color"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente une couleur 24 bits au format RGB avec 8 bits par chaque canal Rouge Vert Bleu. Ne prend pas en charge la transparence."
type: docs
weight: 970
url: /fr/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

Représente une couleur 24 bits au format RGB, avec 8 bits par canal (Rouge, Vert, Bleu). Ne prend pas en charge la transparence.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | Obtient la partie bleue de la couleur sous forme d'entier non signé de 8 bits [0..255] |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | Obtient la partie verte de la couleur sous forme d'entier non signé de 8 bits [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | Indique si cette instance [`Rgb24Color`](../rgb24color) est la valeur par défaut (Noir) - les 3 canaux sont réglés à 0. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | Obtient la partie rouge de la couleur sous forme d'entier non signé de 8 bits [0..255] |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | Crée une valeur [`Rgb24Color`](../rgb24color) à partir des canaux Rouge, Vert, Bleu spécifiés |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | Vérifie l'égalité de cette couleur avec la couleur [`Argb32Color`](../argb32color) spécifiée |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | Vérifie cette couleur avec la couleur non convertie spécifiée |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | Vérifie l'égalité de cette couleur avec la couleur [`Rgb24Color`](../rgb24color) spécifiée |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | Renvoie la luminosité (lightness) Hue‑Saturation‑Lightness (HSL) de cette instance [`Rgb24Color`](../rgb24color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | Renvoie un code de hachage qui définit la couleur actuelle. Non compatible avec GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | Renvoie la valeur de teinte Hue-Saturation-Lightness (HSL), en degrés, pour cette instance [`Rgb24Color`](../rgb24color). Si R == G == B, la teinte n'a aucun sens, et la valeur renvoyée est 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | La saturation Hue-Saturation-Lightness (HSL) pour cette instance [`Rgb24Color`](../rgb24color) |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | Renvoie la valeur ARGB de cette instance [`Rgb24Color`](../rgb24color), compatible avec Color |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | Renvoie cette couleur sous forme de chaîne hexadécimale |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | Sérialise cette instance [`Rgb24Color`](../rgb24color) en notation de fonction CSS 'rgb'. |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | Sérialise cette instance [`Rgb24Color`](../rgb24color) au format 'rgb(r, g, b)' |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | Compare deux couleurs [`Rgb24Color`](../rgb24color) et renvoie un booléen indiquant si les deux correspondent. (2 opérateurs) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | Compare deux couleurs [`Rgb24Color`](../rgb24color) et renvoie un booléen indiquant si les deux ne correspondent pas. (2 opérateurs) |

## Autres membres

| Nom | Description |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | Contient toutes les "couleurs connues", qui ont un nom et une valeur uniques fixes dans la norme CSS |

### Remarques

Ce type est conçu pour être utile aux opérations CSS (mais pas uniquement). Voir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Voir aussi

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
