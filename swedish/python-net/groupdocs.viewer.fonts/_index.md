---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Konfiguration för teckensnittsladdning och -substitution."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Konfiguration för teckensnittsladdning och -substitution.

### Klasser
| Klass | Beskrivning |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Representerar mappen som innehåller TrueType-teckensnitt. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-teckensnitt. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Representerar 4 möjliga stilar för teckensnittet, som används i dokumentet: Regular, Bold, Italic eller Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Representerar ett gemensamt gränssnitt för alla teckensnitt som kan extraheras från alla stödda familjer av dokumentformat: PDF, WordProcessing, Spreadsheet och Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Inkapslar metadata och binär data för ett PDF-teckensnitt som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans, vilket kan vara inbäddat i dokumentet eller installerat på operativsystemet där GroupDocs.Viewer körs. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Representerar metainformation och binär data för ett teckensnitt från ett Presentation-dokument som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans. Teckensnittet används i dokumentets innehåll och kan vara inbäddat i dokumentet eller installerat på operativsystemet där visaren körs. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Inkapslar metainformation och binär data för ett teckensnitt från ett kalkylbladsdokument som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans. Kalkylbladsdokument kan inte ha inbäddade teckensnitt, så ett teckensnitt som returneras av [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) installeras i operativsystemet där visaren körs. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Inkapslar metainformation och binär data för ett teckensnitt från ett WordProcessing-dokument som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans. |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Inkapslar metainformation och binär data för ett teckensnitt från ett WordProcessing-dokument, som ursprungligen inte används i det laddade [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instansdokumentet, men fungerar som ett ersättningsteckensnitt för de som inte kan hittas på målmaskinen. Ersatta teckensnitt finns endast för WordProcessing-formatfamiljen. |

### Enumerationer
| Enum | Beskrivning |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Representerar ett markörgränssnitt för teckensnittskällor. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
