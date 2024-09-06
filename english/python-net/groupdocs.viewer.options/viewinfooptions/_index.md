---
title: ViewInfoOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 250
url: /viewer/python-net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Contains options for retrieving information about view.

The ViewInfoOptions type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|render_comments|Enables rendering comments.|
|render_notes|Enables rendering notes.|
|render_hidden_pages|Enables rendering of hidden pages.|
|default_font_name|Sets the default font for a document.|
|archive_options|The archive files view options.|
|cad_options|The CAD drawing view options.|
|email_options|The email messages view options.|
|outlook_options|The Microsoft Outlook data files view options.|
|mail_storage_options|Mail storage data files view options.|
|pdf_options|The PDF document view options.|
|project_management_options|The project management files view options.|
|spreadsheet_options|The spreadsheet files view options.|
|word_processing_options|The Word processing files view options.|
|visio_rendering_options|The Visio files view options.|
|text_options|Text files view options.|
|presentation_options|The presentation files view options.|
|web_document_options|The Web files view options.|
|extract_text|Enables text extraction.|
|max_width|Sets the maximum width of an output image (in pixels, for rendering to PNG/JPG only).|
|max_height|Sets the maximum height of an output image (in pixels, for rendering to PNG/JPG only).|
|width|The width of the output image (in pixels, for rendering to PNG/JPG only).|
|height|The height of the output image (in pixels, for rendering to PNG/JPG only).|
## Methods
| Name | Description |
| :- | :- |
|for_html_view()|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into HTML.|
|for_html_view(render_single_page)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into HTML.|
|for_jpg_view()|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into JPG.|
|for_jpg_view(extract_text)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into JPG.|
|for_png_view()|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into PNG.|
|for_png_view(extract_text)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into PNG.|
|for_pdf_view()|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into PDF.|
|from_html_view_options(options)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class based on the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) object.|
|from_png_view_options(options)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class based on the [PngViewOptions](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) object.|
|from_jpg_view_options(options)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class based on the [JpgViewOptions](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) object.|
|from_pdf_view_options(options)|Initializes an instance of the [ViewInfoOptions](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class based on the [PdfViewOptions](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) object.|

### See Also

* namespace [groupdocs.viewer.options](/viewer/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

