---
title: "GroupDocs.Viewer.Fonts"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "L'espace de noms fournit des classes et des énumérations pour gérer les polices utilisées pendant le processus de rendu."
type: docs
weight: 50
url: /fr/net/groupdocs.viewer.fonts/
---

L'espace de noms fournit des classes et des énumérations pour gérer les polices utilisées pendant le processus de rendu.

## Classes

| Classe | Description |
| --- | --- |
| [FolderFontSource](./folderfontsource) | Représente le dossier qui contient les polices TrueType. |
| [FontSettings](./fontsettings) | Fournit des méthodes pour travailler avec les sources afin de rechercher des polices TrueType. |
## Structures

| Structure | Description |
| --- | --- |
| [FontStyles](./fontstyles) | Représente les 4 styles possibles de la police, utilisés dans le document : Regular, Bold, Italic ou Bold Italic |
| [PdfFontInfo](./pdffontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant du document PDF, chargée dans l’instance [`Viewer`](../groupdocs.viewer/viewer). Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation où s’exécute **GroupDocs.Viewer**. |
| [PresentationFontInfo](./presentationfontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant du document Presentation, chargée dans l’instance [`Viewer`](../groupdocs.viewer/viewer). Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation où s’exécute **GroupDocs.Viewer**. |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant du document Spreadsheet, chargée dans l’instance [`Viewer`](../groupdocs.viewer/viewer). Les documents Spreadsheet ne peuvent pas contenir de polices intégrées, ainsi cette police particulière, si elle a été renvoyée par la méthode [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts), est installée dans le système d’exploitation où s’exécute **GroupDocs.Viewer**. |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant du document WordProcessing, chargée dans l’instance [`Viewer`](../groupdocs.viewer/viewer). Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation où s’exécute **GroupDocs.Viewer**. |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant d’un document WordProcessing, qui n’est initialement pas utilisée dans le document chargé dans l’instance [`Viewer`](../groupdocs.viewer/viewer), mais sert de police de substitution pour celles qui ne peuvent pas être trouvées sur la machine cible. Les polices de substitution existent uniquement pour la famille de formats WordProcessing. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IFontInfo](./ifontinfo) | Interface commune à toutes les polices, pouvant être extraites de toutes les familles de formats de documents prises en charge : PDF, WordProcessing, Spreadsheet et Presentation. |
| [IFontSource](./ifontsource) | Interface marqueur pour les sources de polices. |
## Énumération

| Énumération | Description |
| --- | --- |
| [FontFormat](./fontformat) | Représente tous les formats de police qui peuvent être présents dans les héritiers de [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo). |
| [SearchOption](./searchoption) | Spécifie s’il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous‑dossiers. |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
