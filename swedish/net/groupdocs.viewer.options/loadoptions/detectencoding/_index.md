---
title: DetectEncoding
second_title: GroupDocs.Viewer för .NET API-referens
description: Detta alternativ aktiverarTXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv  ochCSVgroupdocs.viewer/filetype/csvfiler kodningsdetektering. Om kodningen inte kan upptäckas är standardinställningenEncodinggroupdocs.viewer.options/loadoptions/encoding används.
type: docs
weight: 20
url: /sv/net/groupdocs.viewer.options/loadoptions/detectencoding/
---
## LoadOptions.DetectEncoding property

Detta alternativ aktiverar[`TXT`](../../../groupdocs.viewer/filetype/txt) ,[`TSV`](../../../groupdocs.viewer/filetype/tsv) , och[`CSV`](../../../groupdocs.viewer/filetype/csv)filer kodningsdetektering. Om kodningen inte kan upptäckas är standardinställningen[`Encoding`](../encoding) används.

```csharp
public bool DetectEncoding { get; set; }
```

### Anmärkningar

**Läs mer om att rendera text och tabb-/kommaavgränsade filer**

* [Återge textdokument som HTML-, PDF- och bildfiler](https://docs.groupdocs.com/viewer/net/render-text-files/)
* [Återge Excel- och Apple Numbers-kalkylblad som HTML-, PDF- och bildfiler](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/)

### Exempel

Exemplet visar en typisk användning av detta alternativ.

```csharp
LoadOptions loadOptions = new LoadOptions();
loadOptions.DetectEncoding = true; // Aktivera kodningsdetektering

using (Viewer viewer = new Viewer("employees.csv", loadOptions))
{
    HtmlViewOptions viewOptions = 
        HtmlViewOptions.ForEmbeddedResources();

    viewer.View(viewOptions);
}
```

### Se även

* class [LoadOptions](../../loadoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../loadoptions)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
