---
title: PdfOptimizationOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Reduce output PDF file size applying optimization techniques with different options.
type: docs
weight: 60
url: /net/groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions/
---
## PdfViewOptions.PdfOptimizationOptions property

Reduce output PDF file size applying optimization techniques with different options.

```csharp
public PdfOptimizationOptions PdfOptimizationOptions { get; set; }
```

### Remarks

This option is supported for any input file formats which are supported for conversion to PDF.

* [Supported document formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/)

### Examples

The example demonstrates a typical usage of this option.

```csharp
using (var viewer = new Viewer("cv.docx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.PdfOptimizationOptions = new PdfOptimizationOptions();
    viewOptions.PdfOptimizationOptions.Lineriaze = true;

    viewer.View(viewOptions);
}
```

### See Also

* class [PdfOptimizationOptions](../../pdfoptimizationoptions)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../pdfviewoptions)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->