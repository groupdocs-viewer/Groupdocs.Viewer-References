---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Paketet tillhandahåller klasser och enumerationer för att hantera teckensnitt som används under renderingsprocessen."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/
---

Paketet tillhandahåller klasser och enumerationer för att hantera teckensnitt som används under renderingsprocessen.

De huvudsakliga klasserna och gränssnitten i detta paket är:

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

För mer information om hur du arbetar med typsnitt i GroupDocs.Viewer, se [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Klasser

| Klass | Beskrivning |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Representerar en mapp som innehåller TrueType-typsnitt. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Representerar alla typsnittformat som kan finnas i klassen UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-typsnitt. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Representerar 4 möjliga stilar för typsnittet som används i dokumentet: Regular, Bold, Italic eller Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Inkapslar meta-information och binär data för ett typsnitt från ett PDF-dokument, laddat i Viewer-instansen. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Inkapslar metadata och binär data för ett typsnitt som används i ett presentationsdokument, laddat i Viewer-instansen. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Inkapslar metainformation och binär data för ett typsnitt från ett kalkylbladsdokument, laddat i Viewer-instansen. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Inkapslar metainformation och binär data för ett typsnitt från ett ordbehandlingsdokument, laddat i Viewer-instansen. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Inkapslar metadata och binär data för ett ersatt typsnitt som används i ett ordbehandlingsdokument via GroupDocs.Viewer. |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Markeringsgränssnitt för typsnittskällorna. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Gemensamt gränssnitt för alla typsnitt som kan extraheras från dokumentformat: PDF, WordProcessing, Spreadsheet och Presentation. |

## Enumerationer

| Enum | Beskrivning |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Anger om den aktuella mappen ska sökas, eller den aktuella mappen och alla undermappar. |
