---
title: HtmlViewOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The options for rendering documents into HTML format."
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/
is_root: false
weight: 70
---


## HtmlViewOptions class

The options for rendering documents into HTML format.

The HtmlViewOptions type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#create_page_stream) | Initializes an HtmlViewOptions instance for rendering HTML with embedded resources. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#create_page_stream-release_page_stream) | Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with embedded resources. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#page_stream_factory) | Initializes an HtmlViewOptions instance for rendering into HTML with embedded resources. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/) | Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class with embedded resources. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#file_path_format) | Initializes an HtmlViewOptions instance for embedded resources. |
| [for_embedded_resources_create_page_stream](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_create_page_stream/) |  |
| [for_embedded_resources_file](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_file/) |  |
| [for_embedded_resources_ipage_stream_factory](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_ipage_stream_factory/) |  |
| [for_embedded_resources_string](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_string/) |  |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#create_page_stream-create_resource_stream-create_resource_url) | Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with external resources. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream) | Initializes an instance of the HtmlViewOptions class for rendering into HTML with external resources. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#page_stream_factory-resource_stream_factory) | Initializes an HtmlViewOptions instance for rendering into HTML with external resources. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/) | Initializes an HtmlViewOptions instance configured to generate HTML files with external resources. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#file_path_format-resource_file_path_format-resource_url_format) | Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class. |
| [for_external_resources_create_page_stream](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_create_page_stream/) |  |
| [for_external_resources_file](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_file/) |  |
| [for_external_resources_ipage_stream_factory](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_ipage_stream_factory/) |  |
| [for_external_resources_string](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_string/) |  |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | Applies the clockwise rotation to a page. (inherited from [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  (inherited from [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### Properties
| Property | Description |
| :- | :- |
| [exclude_fonts](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) | The property disables adding any fonts into the HTML document. |
| [fonts_to_exclude](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/) | The list of font names to exclude from HTML document. |
| [for_printing](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_printing/) | The property enables optimization of the output HTML for printing. |
| [image_height](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_height/) | The height of an output image (in pixels). This property is available when converting a single image to HTML only. |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_max_height/) | The maximum height of an output image in pixels. This property is available when converting a single image to HTML only. |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_max_width/) | The max width of an output image (in pixels). This property is available only when converting a single image to HTML. |
| [image_width](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_width/) | The width of the output image (in pixels). |
| [minify](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/minify/) | The property enables HTML content and HTML resources minification. |
| [remove_java_script](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/remove_java_script/) | The property determines whether JavaScript source code is removed from links in the generated HTML documents when rendering input documents that contain scripts. Enabled by default (`True`). |
| [render_responsive](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/render_responsive/) | The property enables responsive rendering. |
| [render_to_single_page](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/render_to_single_page/) | The property enables rendering an entire document to a single HTML file. |
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
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Guides
Task guides that use `HtmlViewOptions`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
