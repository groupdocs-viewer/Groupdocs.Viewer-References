---
title: PdfViewOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents options for rendering documents into PDF format."
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/
is_root: false
weight: 170
---


## PdfViewOptions class

Represents options for rendering documents into PDF format.

For details, see the documentation.

The PdfViewOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream) | Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream-release_file_stream) | Initializes a new PdfViewOptions instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#file_stream_factory) | Initializes a PdfViewOptions instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/) | Initializes a PdfViewOptions instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#output_file_path) | Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) class. |

### Methods
| Method | Description |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | Applies the clockwise rotation to a page. (inherited from [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  (inherited from [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### Properties
| Property | Description |
| :- | :- |
| [image_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/) | The height of an output image in pixels. |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) | The maximum height of an output image in pixels. |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/) | The maximum width of an output image in pixels. |
| [image_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_width/) | The width of the output image in pixels. |
| [pdf_optimization_options](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/pdf_optimization_options/) | The pdf_optimization_options property provides access to a [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/) instance that reduces the output PDF file size by applying optimization techniques. |
| [security](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/security/) | The security options for the output PDF document. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | The archive files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | The CAD drawing view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | The default font for a document used during rendering when a required font is missing. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | The email messages view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | The mail storage data files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | The Microsoft Outlook data files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | The page rotation. (inherited from [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | The PDF document view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | The presentation files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | The project management files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | The property disables rendering comments when set to True. By default it is False, so all comments are displayed. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | The property enables or disables rendering comments. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | The property enables rendering of hidden pages. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | The property enables rendering notes and annotations for some formats. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | The spreadsheet files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | The text options for rendering text files. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | The Visio files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | The text watermark to be applied to each page. (inherited from [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | The Web files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | The Word processing files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Guides
Task guides that use `PdfViewOptions`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
