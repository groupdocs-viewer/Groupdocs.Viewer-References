---
title: ViewInfoOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The options used to retrieve view information."
type: docs
url: /python-net/groupdocs.viewer.options/viewinfooptions/
is_root: false
weight: 330
---


## ViewInfoOptions class

The options used to retrieve view information.

The ViewInfoOptions type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/) | Initializes a ViewInfoOptions instance for retrieving view information when rendering to HTML. |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/#render_single_page) | Initializes a ViewInfoOptions instance for retrieving view information when rendering to HTML. |
| [for_html_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view_boolean/) |  |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/) | Initializes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) instance to retrieve information about view when rendering into JPG. |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/#extract_text) | Initializes a ViewInfoOptions instance for retrieving view information when rendering to JPG. |
| [for_jpg_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view_boolean/) |  |
| [for_pdf_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/) | Initializes a ViewInfoOptions instance for retrieving view information when rendering to PDF. |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into PNG. |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/#extract_text) | Initializes an instance of the ViewInfoOptions class to retrieve information about view when rendering into PNG. |
| [for_png_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view_boolean/) |  |
| [from_html_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/#options) | Initializes an instance of the ViewInfoOptions class based on the HtmlViewOptions object. |
| [from_jpg_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/#options) | Initializes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) instance based on the provided [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/). |
| [from_pdf_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_pdf_view_options/#options) | Initializes a ViewInfoOptions instance from a PdfViewOptions object. |
| [from_png_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_png_view_options/#options) | Initializes a ViewInfoOptions instance from a PngViewOptions object. |

### Properties
| Property | Description |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/extract_text/) | The property enables text extraction. |
| [height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/height/) | The height of the output image (in pixels, for rendering to PNG/JPG only). |
| [max_height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_height/) | The maximum height of an output image (in pixels, for rendering to PNG/JPG only). |
| [max_width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_width/) | The maximum width of an output image in pixels (for rendering to PNG/JPG only). |
| [width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/width/) | The width of the output image (in pixels, for rendering to PNG/JPG only). |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | The archive files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | The CAD drawing view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | The default font for a document used during rendering when a required font is missing. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | The email messages view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | The mail storage data files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | The Microsoft Outlook data files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
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
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | The Web files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | The Word processing files view options. (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Guides
Task guides that use `ViewInfoOptions`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
