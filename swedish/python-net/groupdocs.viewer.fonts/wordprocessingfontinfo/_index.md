---
title: "WordProcessingFontInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Inkapslar metainformation och binär data för ett teckensnitt från ett WordProcessing-dokument som laddats in i en Viewer-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Inkapslar metainformation och binär data för ett teckensnitt från ett WordProcessing-dokument som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans.

Oföränderlig struktur.

Dess instanser skapas och returneras av den offentliga API:n för [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) och bör normalt inte skapas av användaren.

För detaljer, se dokumentationen: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingFontInfo-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Serialiserar teckensnittsinfo som en @font-face-atregel och skriver den till den angivna textskrivaren. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Returnerar felsökningsinformation om denna teckensnittsdata enligt följande mall: \"name style, embedded/system, format\". |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Det alternativa familjenamnet för teckensnittet. Om det saknas, returneras en tom sträng. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Teckenuppsättningen för detta teckensnitt. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Innehållet i detta teckensnitt som en bytearray. Om endast metainformation om detta teckensnitt är tillgänglig och det binära innehållet saknas, returnerar egenskapen None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Familjenamnet för teckensnittet, utan stil; är aldrig None eller en tom sträng. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Formatet för detta teckensnitt. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | Egenskapen indikerar om detta teckensnitt är inbäddat i dokumentet, laddat i [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑instansen (`True`), eller om det är ett systemteckensnitt (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Stilen för teckensnittet — kan vara Regular, Bold, Italic eller Bold Italic. |

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
