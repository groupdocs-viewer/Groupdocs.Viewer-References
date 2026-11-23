---
title: "SpreadsheetFontInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Encapsule les métadonnées et les données binaires d’une police du document Spreadsheet chargé dans le Viewer../groupdocs.viewer/viewer instance. Les documents Spreadsheet ne peuvent pas avoir de polices intégrées, ainsi cette police particulière, si elle a été renvoyée par la méthode GetAllFonts../groupdocs.viewer/viewer/getallfonts, est installée dans le système d’exploitation où s’exécute GroupDocs.Viewer."
type: docs
weight: 870
url: /fr/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Encapsule les métadonnées et les données binaires d’une police du document Spreadsheet, chargé dans l’instance [`Viewer`](../../groupdocs.viewer/viewer). Les documents Spreadsheet ne peuvent pas avoir de polices intégrées, ainsi cette police particulière, si elle a été renvoyée par la méthode [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts), est installée dans le système d’exploitation, où s’exécute GroupDocs.Viewer.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | Jeu de caractères de cette police |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | Couleur de cette police |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | Contenu de cette police sous forme de tableau d'octets. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | Nom de famille de la police, sans style, n'est jamais nul ni une chaîne vide |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | Format de cette police |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | Indique si la police a un seul trait de barré |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | Indique si la police possède un soulignement |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | Style de cette police — peut être Regular, Bold, Italic ou Bold Italic |

## Méthodes

| Nom | Description |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | Sérialise ces informations de police en règle @font-face et les écrit dans le rédacteur de texte spécifié |

### Voir aussi

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
