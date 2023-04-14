---
title: Optimize
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Verminder de grootte van het uitvoerbestand door veelvoorkomende lettertypen zoals Times New Roman en Arial uit te sluiten en andere optimalisatietechnieken toe te passen.
type: docs
weight: 70
url: /nl/net/groupdocs.viewer.options/pdfviewoptions/optimize/
---
## PdfViewOptions.Optimize property

Verminder de grootte van het uitvoerbestand door veelvoorkomende lettertypen zoals Times New Roman en Arial uit te sluiten en andere optimalisatietechnieken toe te passen.

```csharp
public bool Optimize { get; set; }
```

### Opmerkingen

In versie 23.1 wordt deze optie ondersteund[Spreadsheet-bestandsindelingen](https://docs.groupdocs.com/viewer/net/supported-document-formats/#spreadsheet-file-formats) alleen.

Meer informatie over het exporteren van Excel- en Apple Numbers-spreadsheets naar PDF

* [Geef spreadsheets weer als PDF](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/#render-spreadsheets-as-pdf)

### Voorbeelden

Het voorbeeld demonstreert een typisch gebruik van deze optie.

```csharp
using (var viewer = new Viewer("employees.xlsx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.Optimize = true;

    viewer.View(viewOptions);
}
```

### Zie ook

* class [PdfViewOptions](../../pdfviewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../pdfviewoptions)
* montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->