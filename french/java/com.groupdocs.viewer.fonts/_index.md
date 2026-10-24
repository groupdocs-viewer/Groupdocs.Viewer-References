---
title: "com.groupdocs.viewer.fonts"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Le package fournit des classes et des énumérations pour gérer les polices utilisées pendant le processus de rendu."
type: docs
weight: 16
url: /fr/java/com.groupdocs.viewer.fonts/
---

Le package fournit des classes et des énumérations pour gérer les polices utilisées pendant le processus de rendu.

Les principales classes et interfaces de ce paquet sont :

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


Pour plus de détails sur la manipulation des polices dans GroupDocs.Viewer, veuillez vous référer au
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Classes

| Classe | Description |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Représente un dossier contenant des polices TrueType. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Représente tous les formats de police, qui peuvent être présents dans la classe UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Fournit des méthodes pour travailler avec les sources afin de rechercher des polices TrueType. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Représente les 4 styles possibles de la police, utilisés dans le document : Regular, Bold, Italic ou Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Encapsule les méta‑informations et les données binaires d’une police provenant d’un document PDF, chargé dans l’instance Viewer. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Encapsule les métadonnées et les données binaires d’une police utilisée dans un document Presentation, chargé dans l’instance Viewer. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant du document Spreadsheet, chargé dans l’instance Viewer. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Encapsule les métadonnées et les données binaires d’une police provenant du document WordProcessing, chargé dans l’instance Viewer. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Encapsule les métadonnées et les données binaires d’une police substituée utilisée dans un document WordProcessing via GroupDocs.Viewer. |

## Interfaces

| Interface | Description |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Interface marqueur pour les sources de polices. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Interface commune pour toutes les polices pouvant être extraites des formats de documents : PDF, WordProcessing, Spreadsheet et Presentation. |

## Énumérations

| Enum | Description |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Spécifie s’il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous‑dossiers. |
