---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Bevat opties voor het renderen van documenten naar HTML-indeling. Zie voor details het topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ en de onderliggende items."
type: docs
weight: 320
url: /nl/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Bevat opties voor het renderen van documenten naar HTML-indeling. Voor details, zie het [onderwerp](https://docs.groupdocs.com/viewer/net/rendering-to-html/) en de onderliggende items.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergave‑opties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergave‑opties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Stelt het standaardlettertype voor een document in. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergave‑opties voor e‑mailberichten. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Schakelt het toevoegen van lettertypen aan het HTML-document uit. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | De lijst met lettertype-namen die uit het HTML-document moeten worden uitgesloten. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Schakelt optimalisatie van de uitvoer-HTML voor afdrukken in. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | De hoogte van een uitvoerafbeelding (in pixels). De eigenschap is alleen beschikbaar bij het converteren van één afbeelding naar HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Maximale hoogte van een uitvoerafbeelding (in pixels). De eigenschap is alleen beschikbaar bij het converteren van één afbeelding naar HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Maximale breedte van een uitvoerafbeelding (in pixels). De eigenschap is alleen beschikbaar bij het converteren van één afbeelding naar HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | De breedte van de uitvoerafbeelding (in pixels). De eigenschap is alleen beschikbaar bij het converteren van één afbeelding naar HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | De weergave‑opties voor e‑mailopslag‑databestanden. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Schakelt het verkleinen van HTML-inhoud en HTML-resources in. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | De weergave‑opties voor Microsoft Outlook‑databestanden. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | De weergave‑opties voor PDF‑documenten. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | De weergave‑opties voor presentaties. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | De weergave‑opties voor projectmanagement‑bestanden. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Schakelt het renderen van opmerkingen uit wanneer ingesteld op `true`. Standaard is `false` — alle opmerkingen worden weergegeven. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Staat toe om de JavaScript-broncode te verwijderen uit de koppelingen in resulterende HTML-documenten, bij het renderen van invoerdocumenten die scripts bevatten. Standaard is dit ingeschakeld (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Schakelt het renderen van verborgen pagina's in. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Schakelt het renderen van notities en annotaties in voor sommige indelingen. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Schakelt responsief renderen in. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Schakelt het renderen van een heel document naar één HTML-bestand in. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | De weergave‑opties voor spreadsheet‑bestanden. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | De weergave‑opties voor tekstbestanden. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | De weergave‑opties voor Visio‑bestanden. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Het tekstwatermerk dat op elke pagina wordt toegepast. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De weergave‑opties voor webbestanden. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | De weergave‑opties voor tekstverwerkingsbestanden. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde resources. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde resources. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde resources. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse voor het renderen naar HTML met externe resources. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse voor het renderen naar HTML met externe resources. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initialiseert een instantie van de [`HtmlViewOptions`](../htmlviewoptions) klasse voor het renderen naar HTML met externe resources. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Past de klokwijzerrotatie toe op een pagina. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | De paginarotatie. |

### Zie ook

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
