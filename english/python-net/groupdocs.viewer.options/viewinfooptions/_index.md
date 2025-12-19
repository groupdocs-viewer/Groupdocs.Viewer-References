---
title: ViewInfoOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/viewinfooptions/
is_root: false
weight: 250
---

## ViewInfoOptions class

Contains options for retrieving information about view.



**Inheritance:** [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) → 
[`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions)



The ViewInfoOptions type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/render_comments) | Enables rendering comments. |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/render_notes) | Enables rendering notes. |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/render_hidden_pages) | Enables rendering of hidden pages. |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/default_font_name) | Sets the default font for a document. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/archive_options) | The archive files view options. |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/cad_options) | The CAD drawing view options. |
| [email_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/email_options) | The email messages view options. |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/outlook_options) | The Microsoft Outlook data files view options. |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/mail_storage_options) | Mail storage data files view options. |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/pdf_options) | The PDF document view options. |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/project_management_options) | The project management files view options. |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/spreadsheet_options) | The spreadsheet files view options. |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/word_processing_options) | The Word processing files view options. |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/visio_rendering_options) | The Visio files view options. |
| [text_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/text_options) | Text files view options. |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/presentation_options) | The presentation files view options. |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/web_document_options) | The Web files view options. |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/extract_text) | Enables text extraction. |
| [max_width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_width) | Sets the maximum width of an output image (in pixels, for rendering to PNG/JPG only). |
| [max_height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_height) | Sets the maximum height of an output image (in pixels, for rendering to PNG/JPG only). |
| [width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/width) | The width of the output image (in pixels, for rendering to PNG/JPG only). |
| [height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/height) | The height of the output image (in pixels, for rendering to PNG/JPG only). |


### Methods
| Method | Description |
| :- | :- |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/#) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into HTML. |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/#bool) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into HTML. |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/#) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into JPG. |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/#bool) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into JPG. |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/#) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PNG. |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/#bool) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PNG. |
| [for_pdf_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/#) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PDF. |
| [from_html_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/#groupdocs.viewer.options.HtmlViewOptions) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class based on the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) object. |
| [from_png_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_png_view_options/#groupdocs.viewer.options.PngViewOptions) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class based on the [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions) object. |
| [from_jpg_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/#groupdocs.viewer.options.JpgViewOptions) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class based on the [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions) object. |
| [from_pdf_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_pdf_view_options/#groupdocs.viewer.options.PdfViewOptions) | Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions) class based on the [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object. |



### See Also
* module [`groupdocs.viewer.options`](..)
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions)
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions)
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions)
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions)
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions)
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions)
