---
title: PdfViewOptions
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Biedt opties voor het weergeven van documenten in PDFindeling.
type: docs
weight: 420
url: /nl/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Biedt opties voor het weergeven van documenten in PDF-indeling.

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initialiseert nieuw exemplaar van[`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initialiseert nieuw exemplaar van[`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initialiseert nieuw exemplaar van[`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initialiseert nieuw exemplaar van[`PdfViewOptions`](../pdfviewoptions) klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initialiseert nieuw exemplaar van[`PdfViewOptions`](../pdfviewoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergaveopties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergaveopties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standaardlettertype dat moet worden gebruikt wanneer een bepaald lettertype dat in het document wordt gebruikt, niet kan worden gevonden. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergaveopties voor e-mailberichten. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | De hoogte van een uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Max. hoogte van een uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Maximale breedte van een uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | De breedte van het uitvoerbeeld in pixels. (Alleen bij het converteren van een enkele afbeelding naar HTML) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | De kwaliteit van de JPG-afbeeldingen in het PDF-uitvoerdocument; Geldige waarden liggen tussen 1 en 100; Standaardwaarde is 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Weergaveopties voor gegevensbestanden voor e-mailopslag. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Verminder de grootte van het uitvoerbestand door veelvoorkomende lettertypen zoals Times New Roman en Arial uit te sluiten en andere optimalisatietechnieken toe te passen. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | De weergaveopties voor MS Outlook-gegevensbestanden. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | De weergaveopties voor PDF-documenten. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | De weergaveopties voor presentatieverwerkingsdocumenten. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | De weergaveopties voor projectbeheerbestanden. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Maakt weergave van opmerkingen mogelijk. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Maakt weergave van verborgen pagina's mogelijk. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Maakt weergave van notities mogelijk. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | De uitvoer PDF-documentbeveiligingsopties. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | De weergaveopties voor spreadsheetbestanden. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Tekstbestanden splitsen naar pagina-opties. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | De weergaveopties voor Visio-bestanden die documenten verwerken. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Het tekstwatermerk toegepast op elke pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Met deze weergave-opties kunt u het uiterlijk van de HTML/PDF/PNG/JPEG-uitvoer aanpassen bij het weergeven van webdocumenten. |
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
* naamruimte [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
