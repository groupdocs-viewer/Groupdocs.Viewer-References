---
title: "PdfOptions klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar alternativ för att rendera till PDF-dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Representerar alternativ för att rendera till PDF-dokument.

För detaljer, se dokumentationen.

PdfOptions-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Initierar en ny instans av PdfOptions-klassen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | Egenskapen inaktiverar symbolgruppering för exakt symbolplacering under sidrendering. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | Egenskapen inaktiverar skydd mot kopiering av innehåll när man renderar till HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | Egenskapen inaktiverar alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | Egenskapen aktiverar typsnittshintning. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | Egenskapen möjliggör rendering av text och grafik i den ursprungliga PDF-dokumentets z-ordning när man renderar till HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | Alternativet för fast layout möjliggör rendering av PDF- och EPUB-dokument till HTML med en fast layout. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | Utdata bildkvalitet för bildresurser vid rendering till HTML. Standardkvaliteten är `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | Utdata sidstorlek är inställd för att matcha käll-PDF-dokumentets sidstorlek. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | Alternativet möjliggör rendering av texter i PDF-filer som en bild i HTML-utdata. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | Egenskapen som möjliggör att omsluta varje bild i HTML-utdatafilen i en SVG-tagg för att förbättra utdata kvaliteten. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Aktivera typsnittshintning när PDF-sidor renderas till bilder.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
