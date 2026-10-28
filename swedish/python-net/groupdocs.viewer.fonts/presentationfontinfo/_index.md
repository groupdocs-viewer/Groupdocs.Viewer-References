---
title: "PresentationFontInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar metainformation och binära data för ett teckensnitt från ett Presentation-dokument som har laddats in i en Viewer-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Representerar metainformation och binär data för ett teckensnitt från ett Presentation-dokument som laddats in i en [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instans. Teckensnittet används i dokumentets innehåll och kan vara inbäddat i dokumentet eller installerat på operativsystemet där visaren körs.

Typen PresentationFontInfo visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Serialiserar denna teckensnittsinfo som en @font-face-atregel och skriver den till den angivna textskrivaren. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Innehållet i detta teckensnitt som en bytearray. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Familjenamnet för teckensnittet, utan stil; är aldrig None eller en tom sträng. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Formatet för detta teckensnitt. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | Egenskapen indikerar om teckensnittet är inbäddat i dokumentet och laddat in i [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑instansen (`True`), eller om det är ett systemteckensnitt (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Stilen för teckensnittet — kan vara Regular, Bold, Italic eller Bold Italic. |

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
