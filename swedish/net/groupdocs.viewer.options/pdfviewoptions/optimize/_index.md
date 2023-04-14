---
title: Optimize
second_title: GroupDocs.Viewer för .NET API-referens
description: Minska storleken på utdatafilen genom att utesluta vanliga typsnitt som Times New Roman och Arial och använda andra optimeringstekniker.
type: docs
weight: 70
url: /sv/net/groupdocs.viewer.options/pdfviewoptions/optimize/
---
## PdfViewOptions.Optimize property

Minska storleken på utdatafilen genom att utesluta vanliga typsnitt som Times New Roman och Arial, och använda andra optimeringstekniker.

```csharp
public bool Optimize { get; set; }
```

### Anmärkningar

I version 23.1 stöds detta alternativ för[Kalkylbladsfilformat](https://docs.groupdocs.com/viewer/net/supported-document-formats/#spreadsheet-file-formats) endast.

Läs mer om hur du exporterar Excel- och Apple Numbers-kalkylblad till PDF

* [Gör kalkylblad som PDF](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/#render-spreadsheets-as-pdf)

### Exempel

Exemplet visar en typisk användning av detta alternativ.

```csharp
using (var viewer = new Viewer("employees.xlsx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.Optimize = true;

    viewer.View(viewOptions);
}
```

### Se även

* class [PdfViewOptions](../../pdfviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pdfviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->