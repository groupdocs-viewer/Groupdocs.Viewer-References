---
title: "PdfOptimizationOptions klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt de PDF‑optimalisatie‑opties voor die op het uitvoer‑PDF‑bestand moeten worden toegepast."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Stelt de PDF‑optimalisatie‑opties voor die op het uitvoer‑PDF‑bestand moeten worden toegepast.

Voor details en codevoorbeelden, zie de documentatiepagina.

Het PdfOptimizationOptions-type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Initialiseert de standaardwaarden van de MaxResolution-optie op 300 en de ImageQuality-optie op 100. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | De eigenschap maakt compressie van afbeeldingen in het gegenereerde PDF‑bestand mogelijk. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | De eigenschap maakt conversie van het gegenereerde PDF‑bestand naar grijstinten mogelijk. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | De beeldkwaliteit in het gegenereerde PDF‑bestand, uitgedrukt als een percentage. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | De eigenschap maakt optimalisatie van het gegenereerde PDF‑bestand voor online weergave in een webbrowser mogelijk. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | De maximale resolutie in het gegenereerde PDF‑bestand. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | De eigenschap die optimalisatie van spreadsheets in PDF‑bestanden mogelijk maakt. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | De eigenschap maakt het verwijderen van annotaties uit het gegenereerde PDF‑bestand mogelijk. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | De eigenschap maakt het verwijderen van formuliervelden uit een PDF‑bestand mogelijk. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | De eigenschap verwijdert ongebruikte (verweesde) objecten uit een PDF‑bestand. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | De eigenschap verwijdert ongebruikte (verweesde) streams uit een PDF‑bestand die worden verwezen in het paginabronwoordenboek maar nooit worden gebruikt in de paginainhoud. Standaard uitgeschakeld (`False`); instellen op `True` verkleint de grootte van het gegenereerde PDF‑bestand. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | De eigenschap maakt het instellen van de maximale resolutie in het gegenereerde PDF‑bestand mogelijk. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | De eigenschap maakt subsetting van lettertypen in het gegenereerde PDF‑bestand mogelijk. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Linearizatie inschakelen voor snellere webpreview
        view_options.pdf_optimization_options.lineriaze = True
        # Verwijder annotaties en formuliervelden om de grootte te verkleinen
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
