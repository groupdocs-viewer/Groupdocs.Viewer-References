---
title: "PdfFontInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Encapsule les métadonnées et les données binaires d'une police du document PDF chargé dans l'instance Viewer../groupdocs.viewer/viewer. Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d'exploitation où s'exécute GroupDocs.Viewer."
type: docs
weight: 840
url: /fr/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

Encapsule les métadonnées et les données binaires d'une police du document PDF, chargée dans l'instance [`Viewer`](../../groupdocs.viewer/viewer). Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d'exploitation, où GroupDocs.Viewer s'exécute.

```csharp
public struct PdfFontInfo : IFontInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | Contenu de cette police sous forme de tableau d'octets. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | Nom de famille de la police, sans style, n'est jamais nul ni une chaîne vide |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | Format de cette police. Les documents peuvent utiliser des polices dans les formats suivants : TrueType, TrueType Collection, OpenType, Embedded OpenType. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie une valeur Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | Indique si cette police est intégrée dans le document PDF, chargée dans l'instance [`Viewer`](../../groupdocs.viewer/viewer) (`true`), ou non. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | Indique si cette police est présente (installée) dans le système d'exploitation où le GroupDocs.Viewer s'exécute |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | Style de la police — peut être Regular, Bold, Italic ou Bold Italic. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | Sérialise ces informations de police en règle @font-face et les écrit dans le rédacteur de texte spécifié |

### Voir aussi

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
