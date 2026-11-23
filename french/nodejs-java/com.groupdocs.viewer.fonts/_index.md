---
title: "com.groupdocs.viewer.fonts"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Le package fournit des classes et des énumérations pour gérer les polices utilisées pendant le processus de rendu."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/
---

Le package fournit des classes et des énumérations pour gérer les polices utilisées pendant le processus de rendu.

Les principales classes et interfaces de ce package sont :

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

Pour plus de détails sur la gestion des polices dans GroupDocs.Viewer, veuillez consulter la [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Classes

| Classe | Description |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Représente un dossier contenant des polices TrueType. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Représente tous les formats de police, qui peuvent être présents dans la classe UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Fournit des méthodes pour travailler avec les sources afin de rechercher des polices TrueType. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Représente les 4 styles possibles de la police, utilisés dans le document : Regular, Bold, Italic ou Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Encapsule les méta-informations et les données binaires d'une police provenant d'un document PDF, chargée dans l'instance du Viewer. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Encapsule les métadonnées et les données binaires d'une police utilisée dans un document Presentation, chargée dans l'instance du Viewer. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Encapsule les métainformations et les données binaires d'une police provenant du document Spreadsheet, chargée dans l'instance du Viewer. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Encapsule les métainformations et les données binaires d'une police provenant du document WordProcessing, chargée dans l'instance du Viewer. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Encapsule les métadonnées et les données binaires d'une police substituée utilisée dans un document WordProcessing via GroupDocs.Viewer. |

## Interfaces

| Interface | Description |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Interface marqueur pour les sources de polices. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Interface commune à toutes les polices pouvant être extraites des formats de documents : PDF, WordProcessing, Spreadsheet et Presentation. |

## Énumérations

| Énum | Description |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Spécifie s'il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous-dossiers. |
