---
title: PdfOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents options for rendering to PDF documents."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Represents options for rendering to PDF documents.

For details, see the documentation.

The PdfOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Initializes a new instance of the PdfOptions class. |

### Properties
| Property | Description |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | The property disables symbol grouping for precise symbol positioning during page rendering. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | The property disables content copy protection when rendering to HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | The property disables any license restrictions for all fonts in the current XPS/OXPS document. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | The property enables font hinting. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | The property enables rendering text and graphics in the original PDF document's z-order when rendering to HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | The fixed layout option enables rendering PDF and EPUB documents to HTML with a fixed layout. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | The output image quality for image resources when rendering to HTML. The default quality is `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | The output page size is set to match the source PDF document's page size. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | The option enables rendering texts in PDF files as an image in the HTML output. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | The property that enables wrapping each image in the output HTML document in an SVG tag to improve output quality. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Enable font hinting when rendering PDF pages to images.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
