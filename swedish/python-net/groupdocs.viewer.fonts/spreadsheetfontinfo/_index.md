---
title: "Klassen SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Inkapslar metainformation och binära data för ett teckensnitt från ett kalkylbladsdokument som har laddats in i en Viewer-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Inkapslar metainformation och binär data för ett teckensnitt från ett kalkylbladsdokument som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans. Kalkylbladsdokument kan inte ha inbäddade teckensnitt, så ett teckensnitt som returneras av [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) installeras i operativsystemet där visaren körs.

Typen SpreadsheetFontInfo visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Serialiserar teckensnittsinfo som en @font-face-atregel och skriver den till den angivna textskrivaren. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Teckenuppsättningen för detta teckensnitt. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Färgen på detta teckensnitt. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Innehållet i detta teckensnitt som en bytearray. Om endast metainformation om detta teckensnitt är tillgänglig och dess binära innehåll saknas, returnerar egenskapen None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Familjenamnet för teckensnittet, utan stil, är aldrig null eller en tom sträng. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Formatet för detta teckensnitt. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Teckensnittet har en enkel genomstrykning. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Teckensnittet har en understrykning. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Stilen för detta teckensnitt — kan vara Regular, Bold, Italic eller Bold Italic. |

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
