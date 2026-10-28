---
title: "PdfOptimizationOptions-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar PDF-optimeringsalternativen som ska tillämpas på den genererade PDF-filen."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Representerar PDF-optimeringsalternativen som ska tillämpas på den genererade PDF-filen.

För detaljer och kodexempel, se dokumentationssidan.

PdfOptimizationOptions-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Initierar standardvärden för MaxResolution-alternativet till 300 och ImageQuality-alternativet till 100. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | Egenskapen möjliggör komprimering av bilder i den genererade PDF-filen. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | Egenskapen möjliggör konvertering av den genererade PDF-filen till gråskala. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | Bildkvaliteten i den genererade PDF-filen, uttryckt i procent. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | Egenskapen möjliggör optimering av den genererade PDF-filen för visning online med en webbläsare. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | Den maximala upplösningen i den genererade PDF-filen. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | Egenskapen som möjliggör optimering av kalkylblad i PDF-filer. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | Egenskapen möjliggör borttagning av annotationer från den genererade PDF-filen. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | Egenskapen möjliggör borttagning av formulärfält från en PDF-fil. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | Egenskapen tar bort oanvända (föräldralösa) objekt från en PDF-fil. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | Egenskapen tar bort oanvända (föräldralösa) strömmar från en PDF-fil som refereras i sidresursordlistan men aldrig används i sidans innehåll. Inaktiverad som standard (`False`); att sätta den till `True` minskar den genererade PDF-filens storlek. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | Egenskapen möjliggör att ange den maximala upplösningen i den genererade PDF-filen. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | Egenskapen skapar delmängder av teckensnitt i den genererade PDF-filen. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Aktivera linjärisering för snabbare webbpreview
        view_options.pdf_optimization_options.lineriaze = True
        # Ta bort annotationer och formulärfält för att minska storleken
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
