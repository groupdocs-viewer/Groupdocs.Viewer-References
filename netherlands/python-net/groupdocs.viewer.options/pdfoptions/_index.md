---
title: "PdfOptions-klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt opties voor het renderen naar PDF‑documenten voor."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Stelt opties voor het renderen naar PDF‑documenten voor.

Zie voor details de documentatie.

Het PdfOptions-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Initialiseert een nieuwe instantie van de PdfOptions-klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | De eigenschap schakelt symboolgroepering uit voor precieze symboolpositionering tijdens het renderen van de pagina. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | De eigenschap schakelt inhoudskopie-bescherming uit bij het renderen naar HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | De eigenschap schakelt alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | De eigenschap schakelt lettertype-hinting in. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | De eigenschap maakt het mogelijk om tekst en grafische elementen in de oorspronkelijke z-volgorde van het PDF-document te renderen bij het renderen naar HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | De optie vaste lay-out maakt het renderen van PDF- en EPUB-documenten naar HTML met een vaste lay-out mogelijk. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | De uitvoer-afbeeldingskwaliteit voor afbeeldingsbronnen bij het renderen naar HTML. De standaardkwaliteit is `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | De uitvoer-paginagrootte wordt ingesteld om overeen te komen met de paginagrootte van het bron-PDF-document. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | De optie maakt het mogelijk om tekst in PDF-bestanden als afbeelding weer te geven in de HTML-output. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | De eigenschap die het omwikkelen van elke afbeelding in het uitvoer-HTML-document met een SVG-tag mogelijk maakt om de uitvoerkwaliteit te verbeteren. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Schakel lettertype-hinting in bij het renderen van PDF-pagina's naar afbeeldingen.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
