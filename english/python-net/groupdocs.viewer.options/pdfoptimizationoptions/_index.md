---
title: PdfOptimizationOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents PDF optimization options to apply to the output PDF file."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Represents PDF optimization options to apply to the output PDF file.

For details and code samples, see the documentation page.

The PdfOptimizationOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Initializes a new instance of PdfOptimizationOptions with default MaxResolution of 300 and ImageQuality of 100. |

### Properties
| Property | Description |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | The compress_images property enables compressing images in the output PDF file. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | The property enables converting the output PDF file to grayscale. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | The image quality in the output PDF file, expressed as a percentage. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | The property enables optimization of the output PDF file for viewing online with a web browser. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | The maximum resolution in the output PDF file. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | The property enables optimization of spreadsheets in the PDF files. The default value is False. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | The property enables removing annotations from the output PDF file. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | The property enables removing form fields from a PDF file. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | The property removes unused (orphaned) objects from a PDF file, decreasing the output size when set to `True`. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | The property removes unused (orphaned) streams from a PDF file, which are still referenced from the resource dictionary of the page but never used in the page contents. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | The property that enables setting the maximum resolution in the output PDF file. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | The property indicates whether fonts are subset in the output PDF file. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def remove_unused_resources():
    view_options_1 = PdfViewOptions("remove_unused_resources/removed_unused_objects.pdf")
    view_options_1.pdf_optimization_options = PdfOptimizationOptions()
    view_options_1.pdf_optimization_options.remove_unused_objects = True

    view_options_2 = PdfViewOptions("remove_unused_resources/removed_unused_streams.pdf")
    view_options_2.pdf_optimization_options = PdfOptimizationOptions()
    view_options_2.pdf_optimization_options.remove_unused_streams = True

    with Viewer("sample.pdf") as viewer:
        viewer.view(view_options_1)
        viewer.view(view_options_2)

if __name__ == "__main__":
    remove_unused_resources()
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
