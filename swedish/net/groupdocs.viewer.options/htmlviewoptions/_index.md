---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Innehåller alternativ för rendering av dokument till HTML-format. För detaljer se topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ och dess underordnade."
type: docs
weight: 320
url: /sv/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Innehåller alternativ för rendering av dokument till HTML-format. För detaljer, se [ämnet](https://docs.groupdocs.com/viewer/net/rendering-to-html/) och dess underavsnitt.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativ för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Visningsalternativ för CAD-ritningar. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ställer in standardteckensnittet för ett dokument. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visningsalternativ för e-postmeddelanden. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Inaktiverar att lägga till några typsnitt i HTML-dokumentet. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Listan med typsnittsnamn som ska uteslutas från HTML-dokumentet. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Aktiverar optimering av den genererade HTML för utskrift. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Höjden på en utdata bild (i pixlar). Egenskapen är tillgänglig endast när en enda bild konverteras till HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Maximal höjd på en utdata bild (i pixlar). Egenskapen är tillgänglig endast när en enda bild konverteras till HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Maximal bredd på en utdata bild (i pixlar). Egenskapen är tillgänglig endast när en enda bild konverteras till HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Bredden på en utdata bild (i pixlar). Egenskapen är tillgänglig endast när en enda bild konverteras till HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visningsalternativ för e-postlagringsdatafiler. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Aktiverar minifiering av HTML-innehåll och HTML-resurser. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativ för Microsoft Outlook-datafiler. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativ för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visningsalternativ för presentationsfiler. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visningsalternativ för projektledningsfiler. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Inaktiverar rendering av kommentarer när den är satt till `true`. Som standard är den `false` — alla kommentarer visas. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Tillåter att ta bort JavaScript-källkoden från länkarna i de resulterande HTML-dokumenten när inmatningsdokumenten som har skripten renderas. Som standard är den aktiverad (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiverar rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar och annotationer för vissa format |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Aktiverar responsiv rendering. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Aktiverar rendering av ett helt dokument till en HTML‑fil. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativ för kalkylbladsfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Visningsalternativ för textfiler. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visningsalternativ för Visio-filer. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Textvattenstämpeln som ska tillämpas på varje sida. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Visningsalternativ för webbfil. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Visningsalternativ för ordbehandlingsfiler. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions) för rendering till HTML med inbäddade resurser. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions) för rendering till HTML med inbäddade resurser. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions) för rendering till HTML med inbäddade resurser. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions) för rendering till HTML med externa resurser. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions) för rendering till HTML med externa resurser. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initierar en instans av klassen [`HtmlViewOptions`](../htmlviewoptions) för rendering till HTML med externa resurser. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Tillämpar medursrotation på en sida. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sidrotationen. |

### Se även

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
