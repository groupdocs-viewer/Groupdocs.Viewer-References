---
title: PdfOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 140
---

## PdfOptions class

Contains options for rendering to PDF documents. For details, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/).



The PdfOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/#) | Initializes new instance of the [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping) | Disables symbol grouping for precise symbol positioning during page rendering. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering) | Enables rendering text and graphics in the original PDF document's z-order when rendering to HTML. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting) | Enables font hinting. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size) | Sets the output page size the same as the source PDF document's page size. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality) | Sets the output image quality for image resources when rendering to HTML. The default quality is `Low`. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image) | Enables rendering texts in the PDF files as an image in the HTML output. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout) | Enables rendering the PDF and EPUB documents to HTML with a fixed layout. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg) | Enables wrapping each image in the output HTML document in SVG tag to improve the output quality. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications) | Disables any license restrictions for all fonts in the current XPS/OXPS document. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection) | Turns off content copy protection when rendering to HTML. |
| [fix_link_issue](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fix_link_issue) | Tries to fix the issue when whole HTML page content is a link. Works only when input format is PDF and output format is HTML (with embedded or external resources). By default is disabled (`false`). Turn it on only when you know what and why you're doing. Turing this option on increases the document processing time. |



### See Also
* module [`groupdocs.viewer.options`](..)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
