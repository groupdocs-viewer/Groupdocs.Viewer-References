---
title: "PdfFontInfo klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Inkapslar metadata och binär data för ett PDF-teckensnitt som laddats in i en Viewer-instans, vilket kan vara inbäddat i dokumentet eller installerat på operativsystemet där GroupDocs.Viewer körs."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Inkapslar metadata och binär data för ett PDF-teckensnitt som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans, vilket kan vara inbäddat i dokumentet eller installerat på operativsystemet där GroupDocs.Viewer körs.

PdfFontInfo-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Serialiserar denna teckensnittsinfo som en @font-face-atregel och skriver den till den angivna textskrivaren. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Innehållet i detta teckensnitt som en bytearray, eller None om endast metadata är tillgänglig och det binära innehållet saknas. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Familjenamnet för teckensnittet, utan stil; är aldrig None eller en tom sträng. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Formatet för detta teckensnitt. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | Egenskapen indikerar om teckensnittet är inbäddat i PDF-dokumentet och laddat in i Viewer-instansen (`True`), eller inte. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | Egenskapen indikerar om detta teckensnitt finns (installerat) i operativsystemet där GroupDocs.Viewer körs. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Stilen för teckensnittet; kan vara Regular, Bold, Italic eller Bold Italic. |

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
