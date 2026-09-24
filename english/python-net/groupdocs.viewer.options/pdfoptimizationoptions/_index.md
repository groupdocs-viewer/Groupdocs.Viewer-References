---
title: PdfOptimizationOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents the PDF optimization options to apply to the output PDF file."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Represents the PDF optimization options to apply to the output PDF file.

For details and code samples, see the documentation page.

The PdfOptimizationOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Initializes default values of MaxResolution option to 300 and ImageQuality option to 100. |

### Properties
| Property | Description |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | The property enables compressing images in the output PDF file. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | The property enables conversion of the output PDF file to grayscale. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | The image quality in the output PDF file, expressed as a percentage. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | The property enables optimization of the output PDF file for viewing online with a web browser. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | The maximum resolution in the output PDF file. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | The property that enables optimization of spreadsheets in PDF files. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | The property enables removing annotations from the output PDF file. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | The property enables removing form fields from a PDF file. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | The property removes unused (orphaned) objects from a PDF file. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | The property removes unused (orphaned) streams from a PDF file that are referenced in the page resource dictionary but never used in the page contents. Disabled by default (`False`); setting it to `True` reduces the output PDF size. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | The property enables setting the maximum resolution in the output PDF file. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | The property subsets fonts in the output PDF file. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Enable linearization for faster web preview
        view_options.pdf_optimization_options.lineriaze = True
        # Remove annotations and form fields to reduce size
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
