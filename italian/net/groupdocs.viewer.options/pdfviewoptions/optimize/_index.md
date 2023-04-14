---
title: Optimize
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Riduci le dimensioni del file di output escludendo i caratteri comuni come Times New Roman e Arial e applicando altre tecniche di ottimizzazione.
type: docs
weight: 70
url: /it/net/groupdocs.viewer.options/pdfviewoptions/optimize/
---
## PdfViewOptions.Optimize property

Riduci le dimensioni del file di output escludendo i caratteri comuni come Times New Roman e Arial e applicando altre tecniche di ottimizzazione.

```csharp
public bool Optimize { get; set; }
```

### Osservazioni

Nella versione 23.1 questa opzione è supportata per[Formati di file per fogli di calcolo](https://docs.groupdocs.com/viewer/net/supported-document-formats/#spreadsheet-file-formats) solo.

Ulteriori informazioni su come esportare fogli di calcolo Excel e Apple Numbers in PDF

* [Renderizza i fogli di calcolo come PDF](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/#render-spreadsheets-as-pdf)

### Esempi

L'esempio mostra un utilizzo tipico di questa opzione.

```csharp
using (var viewer = new Viewer("employees.xlsx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.Optimize = true;

    viewer.View(viewOptions);
}
```

### Guarda anche

* class [PdfViewOptions](../../pdfviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pdfviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->