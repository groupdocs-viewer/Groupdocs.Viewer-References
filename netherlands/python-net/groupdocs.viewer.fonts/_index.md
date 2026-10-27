---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Lettertype laden en substitutieconfiguratie."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Lettertype laden en substitutieconfiguratie.

### Klassen
| Klasse | Beschrijving |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Stelt de map voor die TrueType-lettertypen bevat. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Biedt methoden voor het werken met bronnen om naar TrueType-lettertypen te zoeken. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Stelt 4 mogelijke stijlen van het lettertype voor, die in het document worden gebruikt: Regular, Bold, Italic, of Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Stelt een gemeenschappelijke interface voor alle lettertypen voor die kunnen worden geëxtraheerd uit alle ondersteunde families van documentformaten: PDF, WordProcessing, Spreadsheet en Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Omvat metadata en binaire gegevens van een PDF-lettertype geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie, die mogelijk in het document is ingebed of geïnstalleerd op het besturingssysteem waarop GroupDocs.Viewer draait. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Stelt metagegevens en binaire gegevens van een lettertype uit een Presentation-document voor, geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie. Het lettertype wordt gebruikt in de documentinhoud en kan ingebed zijn in het document of geïnstalleerd op het besturingssysteem waarop de viewer draait. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Omvat metagegevens en binaire gegevens van een lettertype uit een spreadsheet-document geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie. Spreadsheet-documenten kunnen geen ingebedde lettertypen hebben, dus een lettertype dat wordt geretourneerd door [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) wordt geïnstalleerd op het besturingssysteem waarop de viewer draait. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Omvat metagegevens en binaire gegevens van een lettertype uit een WordProcessing-document geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie. |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Omvat metagegevens en binaire gegevens van één lettertype uit een WordProcessing-document, dat oorspronkelijk niet wordt gebruikt in het geladen [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantiedocument, maar dient als vervangend lettertype voor diegenen die niet op de doelmachine kunnen worden gevonden. Vervangende lettertypen bestaan alleen voor de WordProcessing-formaatfamilie. |

### Enumeraties
| Enum | Beschrijving |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Stelt een markerinterface voor lettertypebronnen voor. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
