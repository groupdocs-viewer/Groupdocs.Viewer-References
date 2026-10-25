---
title: "FontStyles"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente les 4 styles possibles de la police utilisés dans le document Regular, Bold, Italic ou Bold Italic"
type: docs
weight: 810
url: /fr/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

Représente les 4 styles possibles de la police, utilisés dans le document : Regular, Bold, Italic ou Bold Italic

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | Crée une instance [`FontStyles`](../fontstyles) à partir des indicateurs bold et italic spécifiés |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | Indique si cette instance [`FontStyles`](../fontstyles) possède le drapeau **bold** activé (`true`) ou désactivé (`false`) |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | Indique si cette instance [`FontStyles`](../fontstyles) possède le drapeau **italic** activé (`true`) ou désactivé (`false`) |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | Nom de ce style de police |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | Indique si cette instance [`FontStyles`](../fontstyles) est égale à celle spécifiée |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | Indique si cette instance [`FontStyles`](../fontstyles) est égale à la spécifiée non convertie |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | Renvoie un code de hachage de cette instance |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | Renvoie le nom de ce style de police, identique à [`Name`](./name) |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | Tente d’analyser la chaîne brute spécifiée comme un nom de style de police |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | Combine (fusionne) deux styles de police spécifiés et produit un nouveau style de police résultant, où les drapeaux sont fusionnés (union) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | Vérifie si deux valeurs [`FontStyles`](../fontstyles) sont égales |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | Convertit l’instance [`FontStyles`](../fontstyles) spécifiée en l’octet équivalent (champ de bits de 8 bits) dans la plage décimale [0..3] |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | Vérifie si deux valeurs [`FontStyles`](../fontstyles) ne sont pas égales |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | Soustrait le deuxième style de police spécifié (soustrait) du premier style de police spécifié (minuend) et produit un nouveau style de police résultant, où ne sont présents que les drapeaux du premier opérande qui ne se trouvent pas dans le second opérande (différence) |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Style de police Bold (bold uniquement, sans italic) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | Style de police BoldItalic (bold et italic ensemble) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Style de police Italic (italic uniquement, sans bold) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Style de police Regular, valeur par défaut (sans bold et italic) |

### Remarques

Structure immuable avec une API pratique et des opérations de combinaison

### Voir aussi

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
