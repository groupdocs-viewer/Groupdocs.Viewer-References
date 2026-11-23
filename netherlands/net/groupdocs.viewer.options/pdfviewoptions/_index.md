---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Bevat opties voor het renderen van documenten naar PDF-formaat. Zie voor details de documentatie https://docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /nl/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Bevat opties voor het renderen van documenten naar PDF-indeling. Voor details, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initialiseert een instantie van [`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initialiseert een instantie van [`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initialiseert een instantie van [`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initialiseert een instantie van [`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initialiseert een instantie van [`PdfViewOptions`](../pdfviewoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergave‑opties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergave‑opties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Stelt het standaardlettertype voor een document in. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergave‑opties voor e‑mailberichten. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Stelt de hoogte van een uitvoerafbeelding in (in pixels). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Stelt de maximale hoogte van een uitvoerafbeelding in (in pixels). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Stelt de maximale breedte van een uitvoerafbeelding in (in pixels). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Stelt de breedte van een uitvoerafbeelding in (in pixels). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | De weergave‑opties voor e‑mailopslag‑databestanden. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | De weergave‑opties voor Microsoft Outlook‑databestanden. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Vermindert de grootte van het uitvoer‑PDF‑bestand door optimalisatietechnieken toe te passen met verschillende opties. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | De weergave‑opties voor PDF‑documenten. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | De weergave‑opties voor presentaties. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | De weergave‑opties voor projectmanagement‑bestanden. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Schakelt het renderen van opmerkingen uit wanneer ingesteld op `true`. Standaard is `false` — alle opmerkingen worden weergegeven. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Schakelt het renderen van verborgen pagina's in. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Schakelt het renderen van notities en annotaties in voor sommige indelingen. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Stelt de beveiligingsopties van het uitvoer‑PDF‑document in. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | De weergave‑opties voor spreadsheet‑bestanden. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | De weergave‑opties voor tekstbestanden. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | De weergave‑opties voor Visio‑bestanden. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Het tekstwatermerk dat op elke pagina wordt toegepast. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De weergave‑opties voor webbestanden. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | De weergave‑opties voor tekstverwerkingsbestanden. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
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
