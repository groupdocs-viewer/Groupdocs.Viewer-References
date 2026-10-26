---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Il pacchetto fornisce classi ed enumerazioni per gestire i font utilizzati durante il processo di rendering."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.viewer.fonts/
---

Il pacchetto fornisce classi ed enumerazioni per gestire i font utilizzati durante il processo di rendering.

Le classi e le interfacce principali in questo pacchetto sono:

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

Per ulteriori dettagli su come lavorare con i font in GroupDocs.Viewer, consultare la [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Classi

| Classe | Descrizione |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Rappresenta una cartella che contiene font TrueType. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Rappresenta tutti i formati di font, che possono essere presenti nella classe UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Rappresenta 4 possibili stili del font, usati nel documento: Regular, Bold, Italic o Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Incapsula meta-informazioni e dati binari di un font da un documento PDF, caricato nell'istanza Viewer. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Incapsula metadati e dati binari di un font usato in un documento Presentation, caricato nell'istanza Viewer. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Incapsula metainformazioni e dati binari di un font da un documento Spreadsheet, caricato nell'istanza Viewer. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Incapsula metainformazioni e dati binari di un font da un documento WordProcessing, caricato nell'istanza Viewer. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Incapsula metadati e dati binari di un font sostituito usato in un documento WordProcessing tramite GroupDocs.Viewer. |

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Interfaccia marker per le sorgenti dei font. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Interfaccia comune per tutti i font che possono essere estratti dai formati di documento: PDF, WordProcessing, Spreadsheet e Presentation. |

## Enumerazioni

| Enum | Descrizione |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Specifica se cercare nella cartella corrente, o nella cartella corrente e in tutte le sottocartelle. |
