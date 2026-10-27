---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Het pakket biedt klassen en enumeraties om lettertypen te beheren die tijdens het renderproces worden gebruikt."
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.viewer.fonts/
---

Het pakket biedt klassen en enumeraties om lettertypen te beheren die tijdens het renderproces worden gebruikt.

De belangrijkste klassen en interfaces in dit pakket zijn:

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

Voor meer details over het werken met lettertypen in GroupDocs.Viewer, raadpleeg de [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Stelt een map voor die TrueType-lettertypen bevat. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Stelt alle lettertypeformaten voor, die aanwezig kunnen zijn in de UsedFontInfo-klasse. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Biedt methoden voor het werken met bronnen om TrueType-lettertypen te zoeken. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Stelt 4 mogelijke stijlen van het lettertype voor, gebruikt in het document: Regular, Bold, Italic of Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Omvat meta-informatie en binaire gegevens van één lettertype uit een PDF-document, geladen in de Viewer-instantie. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Omvat metadata en binaire gegevens van een lettertype dat wordt gebruikt in een Presentatiedocument, geladen in de Viewer-instantie. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Omvat metagegevens en binaire gegevens van één lettertype uit het Spreadsheet-document, geladen in de Viewer-instantie. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Omvat metagegevens en binaire gegevens van één lettertype uit het WordProcessing-document, geladen in de Viewer-instantie. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Omvat metadata en binaire gegevens van één vervangen lettertype dat wordt gebruikt in een WordProcessing-document via GroupDocs.Viewer. |

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Markerinterface voor de lettertypebronnen. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Gemeenschappelijke interface voor alle lettertypen die kunnen worden geëxtraheerd uit documentformaten: PDF, WordProcessing, Spreadsheet en Presentation. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Specificeert of de huidige map moet worden doorzocht, of de huidige map en alle submappen. |
