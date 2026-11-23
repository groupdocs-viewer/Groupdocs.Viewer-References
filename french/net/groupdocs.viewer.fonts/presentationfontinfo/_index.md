---
title: "PresentationFontInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Encapsule les métadonnées et les données binaires d’une police du document Presentation chargé dans le Viewer../groupdocs.viewer/viewer instance. Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation où s’exécute GroupDocs.Viewer."
type: docs
weight: 850
url: /fr/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Encapsule les métadonnées et les données binaires d’une police du document Presentation, chargé dans l’instance [`Viewer`](../../groupdocs.viewer/viewer). Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation, où s’exécute GroupDocs.Viewer.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | Contenu de cette police sous forme de tableau d'octets. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | Nom de famille de la police, sans style, n'est jamais nul ni une chaîne vide |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | Format de cette police. Les documents peuvent utiliser des polices dans les formats suivants : TrueType, TrueType Collection, OpenType, Embedded OpenType. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie une valeur Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | Indique si cette police est intégrée dans le document, chargée dans l’instance [`Viewer`](../../groupdocs.viewer/viewer) (`true`), ou s’il s’agit d’une police système (`false`). Les documents Spreadsheet ne peuvent pas contenir de polices intégrées, ainsi cette propriété renvoie toujours `false`. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | Style de la police — peut être Regular, Bold, Italic ou Bold Italic |

## Méthodes

| Nom | Description |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | Sérialise ces informations de police en règle @font-face et les écrit dans le rédacteur de texte spécifié |

### Voir aussi

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
