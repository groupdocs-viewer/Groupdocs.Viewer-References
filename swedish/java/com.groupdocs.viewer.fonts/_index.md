---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Paketet tillhandahåller klasser och uppräkningar för att hantera typsnitt som används under renderingsprocessen."
type: docs
weight: 16
url: /sv/java/com.groupdocs.viewer.fonts/
---

Paketet tillhandahåller klasser och uppräkningar för att hantera typsnitt som används under renderingsprocessen.

De viktigaste klasserna och gränssnitten i detta paket är:

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


För mer information om hur du arbetar med teckensnitt i GroupDocs.Viewer, se
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Representerar en mapp som innehåller TrueType-teckensnitt. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Representerar alla teckensnittformat som kan finnas i klassen UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-teckensnitt. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Representerar 4 möjliga stilar för teckensnittet som används i dokumentet: Regular, Bold, Italic eller Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Inkapslar meta‑information och binär data för ett teckensnitt från ett PDF‑dokument, laddat i Viewer‑instansen. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Inkapslar metadata och binär data för ett teckensnitt som används i ett presentationsdokument, laddat i Viewer‑instansen. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Inkapslar metainformation och binär data för ett teckensnitt från ett kalkylbladsdokument, laddat i Viewer‑instansen. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Inkapslar metainformation och binär data för ett teckensnitt från ett ordbehandlingsdokument, laddat i Viewer‑instansen. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Inkapslar metadata och binär data för ett ersatt teckensnitt som används i ett ordbehandlingsdokument via GroupDocs.Viewer. |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Markeringsgränssnitt för teckensnittskällorna. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Gemensamt gränssnitt för alla teckensnitt som kan extraheras från dokumentformat: PDF, WordProcessing, Spreadsheet och Presentation. |

## Enumerationer

| Enum | Beskrivning |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Anger om du ska söka i den aktuella mappen, eller i den aktuella mappen och alla undermappar. |
