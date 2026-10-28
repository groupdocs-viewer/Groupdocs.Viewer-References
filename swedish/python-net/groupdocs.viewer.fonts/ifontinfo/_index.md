---
title: "IFontInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar ett gemensamt gränssnitt för alla teckensnitt som kan extraheras från alla stödda familjer av dokumentformat: PDF, WordProcessing, Spreadsheet och Presentation."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Representerar ett gemensamt gränssnitt för alla teckensnitt som kan extraheras från alla stödda familjer av dokumentformat: PDF, WordProcessing, Spreadsheet och Presentation.

Typen IFontInfo exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Serialiserar denna teckensnittsinfo som en @font-face-atregel och skriver den till den angivna textskrivaren. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Det binära innehållet i teckensnittet som en bytearray, om tillgängligt, eller None om det inte är det. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Familjenamnet för teckensnittet som en sträng. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Formatet för detta teckensnitt som en enum — TrueType, TrueType Collection, OpenType, Embedded OpenType, eller `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Stilen för teckensnittet som en enum (Regular, Bold, Italic eller Bold Italic); vissa dokumentformat kan endast stödja [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
