---
title: PdfOptimizationOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Use this class to specify PDF optimization options to apply to the output PDF file.
type: docs
weight: 380
url: /net/groupdocs.viewer.options/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Use this class to specify PDF optimization options to apply to the output PDF file.

```csharp
public class PdfOptimizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Sets up default values of MaxResolution option to 300 and ImageQuality option to 100 |

## Properties

| Name | Description |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | If the source PDF file contains images, consider compressing the images and setting their quality. In order to enable image compression, set this option to true. All the images in a document will be re-compressed. The compression is defined by the ImageQuality property, which is the value of the quality in percent. 100% is unchanged quality. To decrease image quality, set the ImageQuality property less than 100. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | PDF file is comprised of Text, Image, Attachment, Annotations, Graphs and other objects. You may come across a requirement to convert a PDF from RGB colorspace to grayscale so that it would be faster while printing those PDF files. Also when the file is converted to grayscale, the size of the document is also reduced but with this change, the quality of the document may drop. Currently, this feature is supported by the Pre-Flight feature of Adobe Acrobat. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | If the source PDF file contains images, consider compressing the images and setting their quality. In order to enable image compression, set CompressImages option to true. All the images in a document will be re-compressed. The compression is defined by the ImageQuality property, which is the value of the quality in percent. 100% is unchanged quality. To decrease image quality, set the CompressImages option to true and ImageQuality property less than 100. |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Optimizes output PDF for online browsing with a web browser. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Can be used with CompressImage option to resize the images with a lower resolution. In this case, we should set CompressImage to true, ResizeImages to true and MaxResolution to the appropriate value. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | Optimize Excel spreadsheets border lines and fonts for smaller output file size. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Annotations can be deleted when they are unnecessary. When they are needed but do not require additional editing, they can be flattened. It will reduce the file size. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | If the PDF document contains AcroForms, we can try to reduce the file size by flattening form fields. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Can be used with CompressImage option to resize the images with a lower resolution. In this case, we should set CompressImage to true, ResizeImages to true and MaxResolution to the appropriate value. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Every font used to display text on the page contains set of glyphs for font characters. PDF specification supports "font subset" i.e. font with only those glyphs which are used. This may cause issues when text should be updated (since probably required glyphs are absent in the font), but for the document which is not planned to change this allows to decrease size. |

### Remarks

These optimization options are supported for any input file formats which are supported for export to PDF.

* [Supported document formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/)

### Examples

The example demonstrates a default usage of this class.

```csharp
using (var viewer = new Viewer("sample.docx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.PdfOptimizationOptions = new PdfOptimizationOptions();
    viewOptions.PdfOptimizationOptions.Lineriaze = true;

    viewer.View(viewOptions);
}
```

### See Also

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
