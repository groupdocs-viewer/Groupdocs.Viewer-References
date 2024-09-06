---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 70
url: /python-net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Contains options for rendering documents into HTML format. For details, see the

The HtmlViewOptions type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|render_comments|  |
|render_notes|  |
|render_hidden_pages|  |
|default_font_name|  |
|archive_options|  |
|cad_options|  |
|email_options|  |
|outlook_options|  |
|mail_storage_options|  |
|pdf_options|  |
|project_management_options|  |
|spreadsheet_options|  |
|word_processing_options|  |
|visio_rendering_options|  |
|text_options|  |
|presentation_options|  |
|web_document_options|  |
|watermark|The text watermark to be applied to each page.|
|render_responsive|Enables responsive rendering.|
|minify|Enables HTML content and HTML resources minification.|
|render_to_single_page|Enables rendering an entire document to one HTML file.|
|image_max_width|Max width of an output image (in pixels). The property is available when converting single image to HTML only.|
|image_max_height|Max height of an output image (in pixels). The property is available when converting single image to HTML only.|
|image_width|The width of the output image (in pixels). The property is available when converting single image to HTML only.|
|image_height|The height of an output image (in pixels). The property is available when converting single image to HTML only.|
|for_printing|Enables optimization the output HTML for printing.|
|exclude_fonts|Disables adding any fonts into HTML document.|
|fonts_to_exclude|The list of font names to exclude from HTML document.|
## Methods
| Name | Description |
| :- | :- |
|for_embedded_resources(page_stream_factory)|Initializes an instance of the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with embedded resources.|
|for_embedded_resources()|Initializes an instance of the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with embedded resources.|
|for_embedded_resources(file_path_format)|Initializes an instance of the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class.|
|for_external_resources(page_stream_factory, resource_stream_factory)|Initializes an instance of the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with external resources.|
|for_external_resources()|Initializes an instance of the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with external resources.|
|for_external_resources(file_path_format, resource_file_path_format, resource_url_format)|Initializes an instance of the [HtmlViewOptions](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class.|
|rotate_page(page_number, rotation)|Applies the clockwise rotation to a page.|

### See Also

* namespace [groupdocs.viewer.options](/viewer/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

