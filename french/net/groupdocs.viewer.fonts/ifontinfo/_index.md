---
title: "IFontInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Interface commune pour toutes les polices qui peuvent être extraites de toutes les familles prises en charge des formats de documents PDF, WordProcessing, Spreadsheet et Presentation."
type: docs
weight: 820
url: /fr/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

Interface commune à toutes les polices, pouvant être extraites de toutes les familles de formats de documents prises en charge : PDF, WordProcessing, Spreadsheet et Presentation.

```csharp
public interface IFontInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | Contenu binaire de la police sous forme de tableau d'octets, si disponible, ou `null`, sinon |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | Nom de famille de la police sous forme de chaîne |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | Format de cette police en tant qu'énumération — TrueType, TrueType Collection, OpenType, Embedded OpenType ou Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | Style de la police en tant qu'énumération — Regular, Bold, Italic ou Bold Italic. Certains formats de documents peuvent ne disposer que d'un style [`Regular`](../fontstyles/regular). |

## Méthodes

| Nom | Description |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | Sérialise ces informations de police en règle @font-face et les écrit dans le rédacteur de texte spécifié |

### Voir aussi

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
