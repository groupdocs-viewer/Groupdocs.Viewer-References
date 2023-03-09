---
title: HtmlViewOptions
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Biedt opties voor het weergeven van documenten in HTMLindeling.
type: docs
weight: 330
url: /nl/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Biedt opties voor het weergeven van documenten in HTML-indeling.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergaveopties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergaveopties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standaardlettertype dat moet worden gebruikt wanneer een bepaald lettertype dat in het document wordt gebruikt, niet kan worden gevonden. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergaveopties voor e-mailberichten. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Indien ingeschakeld, wordt voorkomen dat er lettertypen aan een HTML-document worden toegevoegd. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | De lijst met lettertypenamen die moeten worden uitgesloten van HTML-document. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Geeft aan of uitvoer HTML moet worden geoptimaliseerd voor afdrukken. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | De hoogte van een uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Max. hoogte van een uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Maximale breedte van een uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | De breedte van het uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Weergaveopties voor gegevensbestanden voor e-mailopslag. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Maakt minificatie van HTML-inhoud en HTML-bronnen mogelijk. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | De weergaveopties voor MS Outlook-gegevensbestanden. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | De weergaveopties voor PDF-documenten. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | De weergaveopties voor presentatieverwerkingsdocumenten. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | De weergaveopties voor projectbeheerbestanden. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Maakt weergave van opmerkingen mogelijk. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Maakt weergave van verborgen pagina's mogelijk. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Maakt weergave van notities mogelijk. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Maakt responsieve weergave mogelijk; Responsieve webpagina's worden goed weergegeven op apparaten met een ander schermformaat. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Maakt weergave van een volledig document naar één HTML-bestand mogelijk. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | De weergaveopties voor spreadsheetbestanden. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Tekstbestanden splitsen naar pagina-opties. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | De weergaveopties voor Visio-bestanden die documenten verwerken. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Het tekstwatermerk toegepast op elke pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Met deze weergave-opties kunt u het uiterlijk van de HTML/PDF/PNG/JPEG-uitvoer aanpassen bij het weergeven van webdocumenten. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Met deze weergave-opties kunt u het uiterlijk van de uitvoer HTML/PDF/PNG/JPEG aanpassen bij het renderen van Word-documenten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse voor weergave in HTML met ingesloten bronnen. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse voor weergave in HTML met ingesloten bronnen. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse voor weergave in HTML met ingesloten bronnen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse voor weergave in HTML met externe bronnen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse voor weergave in HTML met externe bronnen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../htmlviewoptions) klasse voor weergave in HTML met externe bronnen. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Past rechtsom draaien toe op de pagina. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | De paginarotaties. |

### Zie ook

* class [ViewOptions](../viewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
