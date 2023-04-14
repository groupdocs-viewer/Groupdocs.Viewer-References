---
title: FixedLayout
second_title: GroupDocs.Viewer för .NET API-referens
description: PDF är ett fast format så att alla element har en specifik plats på en sida. För att säkerställa att utdataHTML ser ut på samma sätt som källPDFdokumenten renderas dokumenten till HTML med en fast layout som standard. Vid rendering med fast layout HTMLutdata har fast storlek så att elementen stannar på samma plats oavsett fönsterstorlek. För att rendera till HTML med flytande layout ställ in den här egenskapen tillfalsk .
type: docs
weight: 50
url: /sv/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---
## PdfOptions.FixedLayout property

PDF är ett fast format så att alla element har en specifik plats på en sida. För att säkerställa att utdata-HTML ser ut på samma sätt som käll-PDF-dokumenten renderas dokumenten till HTML med en fast layout som standard. Vid rendering med fast layout HTML-utdata har fast storlek så att elementen stannar på samma plats oavsett fönsterstorlek. För att rendera till HTML med flytande layout ställ in den här egenskapen till`falsk` .

```csharp
public bool FixedLayout { get; set; }
```

### Anmärkningar

Standardvärdet är`Sann` .

Det här alternativet stöds vid rendering till HTML.

När du renderar till flytande layout hoppas bilderna över. Använd flytande layout när du renderar PDF-dokument med textinnehåll.

### Exempel

Det här exemplet visar hur man renderar PDF-dokument till HTML med flytande layout.

```csharp
using GroupDocs.Viewer;
using GroupDocs.Viewer.Options;
//..

using (var viewer = new Viewer("resume.pdf"))
{
   var viewOptions = HtmlViewOptions.ForEmbeddedResources("page_{0}.html");
   viewOptions.FixedLayout = false;
   viewer.View(viewOptions);
}        
```

### Se även

* class [PdfOptions](../../pdfoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pdfoptions)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->