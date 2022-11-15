---
title: HtmlViewOptions
second_title: GroupDocs.Viewer för .NET API-referens
description: Ger alternativ för att rendera dokument till HTMLformat.
type: docs
weight: 330
url: /sv/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Ger alternativ för att rendera dokument till HTML-format.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativen för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Alternativen för CAD-ritningsvy. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardteckensnitt som ska användas när ett visst teckensnitt som används i dokumentet inte kan hittas. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visa alternativen för e-postmeddelanden. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | När aktiverad förhindrar du att lägga till några teckensnitt i HTML-dokument. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Listan över teckensnittsnamn som ska uteslutas från HTML-dokument. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Indikerar om HTML-utdata ska optimeras för utskrift. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Höjden på en utdatabild i pixlar. (När du konverterar en bild till endast HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Maxhöjd för en utdatabild i pixlar. (När du konverterar en bild till endast HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Max bredd på en utdatabild i pixlar. (När du konverterar en bild till endast HTML) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Bredden på utdatabilden i pixlar. (När du konverterar en bild till endast HTML) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visa alternativ för e-postlagringsdatafiler. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Aktiverar HTML-innehåll och HTML-resurser minifiering. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativen för MS Outlook-datafiler. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativen för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visa alternativ för presentationsbearbetning av dokument. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visa alternativ för projekthanteringsfiler. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Möjliggör rendering av kommentarer. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Möjliggör rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Möjliggör responsiv rendering; Responsiva webbsidor återges bra på enheter med olika skärmstorlekar. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Aktiverar HTML-innehåll kommer att renderas till en sida |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativen för kalkylarksfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Textfiler som delar upp till sidoralternativ. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio-filer som behandlar dokumentvyalternativ. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Textens vattenstämpel som appliceras på varje sida. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De här renderingsalternativen gör att du kan anpassa utseendet på HTML/PDF/PNG/JPEG-utdata när du renderar webbdokument. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Med de här renderingsalternativen kan du anpassa utseendet på utdata HTML/PDF/PNG/JPEG när du renderar Word-dokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) klass för rendering till HTML med inbäddade resurser. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) klass för rendering till HTML med inbäddade resurser. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) klass för rendering till HTML med inbäddade resurser. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) klass för rendering till HTML med externa resurser. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) klass för rendering till HTML med externa resurser. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initierar ny instans av[`HtmlViewOptions`](../htmlviewoptions) klass för rendering till HTML med externa resurser. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Tillämpar medurs rotation på sidan. |

## Fält

| namn | Beskrivning |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sidrotationerna. |

### Se även

* class [ViewOptions](../viewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* hopsättning [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
