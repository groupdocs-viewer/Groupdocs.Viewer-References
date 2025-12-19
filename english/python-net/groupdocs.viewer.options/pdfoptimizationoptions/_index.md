---
title: PdfOptimizationOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 130
---

## PdfOptimizationOptions class

Contains the PDF optimization options to apply to the output PDF file. For details and code samples, see this [page](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) and its children.



The PdfOptimizationOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/#) | Sets up default values of MaxResolution option to 300 and ImageQuality option to 100 |


### Properties
| Property | Description |
| :- | :- |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) | Enables optimization the output PDF file for viewing online with a web browser. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations) | Enables removing annotation from the output PDF file. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields) | Enables removing form fields from a PDF file. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale) | Enables converting the output PDF file to a grayscale. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts) | Subsets fonts in the output PDF file. |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images) | Enables compressing images in the output PDF file. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality) | Sets the image quality in the output PDF file (in percent). |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images) | Enables setting the maximum resolution in the output PDF file. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution) | Sets the maximum resolution in the output PDF file. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets) | Enables optimization of spreadsheets in the PDF files. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects) | Removes unused (orphaned) objects from a PDF file, which are placed in the PDF document, but are not referenced from resource dictionaries of any page and thus are not used at all. Activating this property (`true`) will decrease the output PDF document size. By default is disabled (`false`). |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams) | Removes unused (orphaned) streams from a PDF file, which are still referenced from the resource dictionary of the page, but actually are never used in the page contents. By default is disabled (`false`), its enabling (`true`) will decrease the output PDF document size. |



### See Also
* module [`groupdocs.viewer.options`](..)
