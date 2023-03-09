---
title: PngViewOptions
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Biedt opties voor het weergeven van documenten in PNGindeling.
type: docs
weight: 440
url: /nl/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

Biedt opties voor het weergeven van documenten in PNG-indeling.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Initialiseert nieuw exemplaar van[`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Initialiseert nieuw exemplaar van[`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Initialiseert nieuw exemplaar van[`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Initialiseert nieuw exemplaar van[`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initialiseert nieuw exemplaar van[`PngViewOptions`](../pngviewoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergaveopties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergaveopties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standaardlettertype dat moet worden gebruikt wanneer een bepaald lettertype dat in het document wordt gebruikt, niet kan worden gevonden. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergaveopties voor e-mailberichten. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Schakelt tekstextractie in. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | De hoogte van een uitvoerbeeld in pixels. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Weergaveopties voor gegevensbestanden voor e-mailopslag. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Max. hoogte van een uitvoerbeeld in pixels. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Maximale breedte van een uitvoerbeeld in pixels. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | De weergaveopties voor MS Outlook-gegevensbestanden. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | De weergaveopties voor PDF-documenten. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | De weergaveopties voor presentatieverwerkingsdocumenten. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | De weergaveopties voor projectbeheerbestanden. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Maakt weergave van opmerkingen mogelijk. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Maakt weergave van verborgen pagina's mogelijk. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Maakt weergave van notities mogelijk. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | De weergaveopties voor spreadsheetbestanden. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Tekstbestanden splitsen naar pagina-opties. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | De weergaveopties voor Visio-bestanden die documenten verwerken. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Het tekstwatermerk toegepast op elke pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Met deze weergave-opties kunt u het uiterlijk van de HTML/PDF/PNG/JPEG-uitvoer aanpassen bij het weergeven van webdocumenten. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | De breedte van het uitvoerbeeld in pixels. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Met deze weergave-opties kunt u het uiterlijk van de uitvoer HTML/PDF/PNG/JPEG aanpassen bij het renderen van Word-documenten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Past rechtsom draaien toe op de pagina. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | De paginarotaties. |

### Zie ook

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* naamruimte [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
