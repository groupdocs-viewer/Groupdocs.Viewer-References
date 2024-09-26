---
title: PdfOptimizationOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 130
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Contains the PDF optimization options to apply to the output PDF file. For details and code samples, see this

The PdfOptimizationOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfOptimizationOptions()|Sets up default values of MaxResolution option to 300 and ImageQuality option to 100|
## Properties
| Name | Description |
| :- | :- |
|lineriaze|Enables optimization the output PDF file for viewing online with a web browser.|
|remove_annotations|Enables removing annotation from the output PDF file.|
|remove_form_fields|Enables removing form fields from a PDF file.|
|convert_to_gray_scale|Enables converting the output PDF file to a grayscale.|
|subset_fonts|Subsets fonts in the output PDF file.|
|compress_images|Enables compressing images in the output PDF file.|
|image_quality|Sets the image quality in the output PDF file (in percent).|
|resize_images|Enables setting the maximum resolution in the output PDF file.|
|max_resolution|Sets the maximum resolution in the output PDF file.|
|optimize_spreadsheets|Enables optimization of spreadsheets in the PDF files.|
|remove_unused_objects|Removes unused (orphaned) objects from a PDF file, which are placed in the PDF document, but are not referenced from resource dictionaries of any page and thus are not used at all. Activating this property (|
|remove_unused_streams|Removes unused (orphaned) streams from a PDF file, which are still referenced from the resource dictionary of the page, but actually are never used in the page contents. By default is disabled (|

### See Also

* namespace [groupdocs.viewer.options](/viewer/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

