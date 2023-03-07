---
title: PdfViewOptions
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Bietet Optionen zum Rendern von Dokumenten im PDFFormat.
type: docs
weight: 420
url: /de/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Bietet Optionen zum Rendern von Dokumenten im PDF-Format.

```csharp
public class PdfViewOptions : ViewOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initialisiert eine neue Instanz von[`PdfViewOptions`](../pdfviewoptions) Klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initialisiert eine neue Instanz von[`PdfViewOptions`](../pdfviewoptions) Klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initialisiert eine neue Instanz von[`PdfViewOptions`](../pdfviewoptions) Klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initialisiert eine neue Instanz von[`PdfViewOptions`](../pdfviewoptions) Klasse. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initialisiert eine neue Instanz von[`PdfViewOptions`](../pdfviewoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Anzeigeoptionen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardschriftart, die verwendet wird, wenn eine bestimmte Schriftart, die im Dokument verwendet wird, nicht gefunden werden kann. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die Anzeigeoptionen für E-Mail-Nachrichten. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Die Höhe eines Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Maximale Höhe eines Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Maximale Breite eines Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Die Breite des Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | Die Qualität der im ausgegebenen PDF-Dokument enthaltenen JPG-Bilder; Gültige Werte liegen zwischen 1 und 100; Der Standardwert ist 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für E-Mail-Speicherdatendateien. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Reduzieren Sie die Größe der Ausgabedatei, indem Sie gängige Schriftarten wie Times New Roman und Arial ausschließen und andere Optimierungstechniken anwenden. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Die Ansichtsoptionen für MS Outlook-Datendateien. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Die Anzeigeoptionen für PDF-Dokumente. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Die Anzeigeoptionen für Präsentationsverarbeitungsdokumente. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Die Ansichtsoptionen für Projektverwaltungsdateien. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Aktiviert das Rendern von Kommentaren. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiviert das Rendern versteckter Seiten. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiviert das Rendern von Notizen. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Die Sicherheitsoptionen für das PDF-Ausgabedokument. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Die Anzeigeoptionen für Tabellenkalkulationsdateien. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Optionen zum Aufteilen von Textdateien in Seiten. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Die Optionen für die Ansicht von Visio-Dateien, die Dokumente verarbeiten. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Das auf jede Seite angewendete Textwasserzeichen. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Mit diesen Rendering-Optionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Webdokumenten anpassen. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Mit diesen Wiedergabeoptionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Word-Dokumenten anpassen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Dreht die Seite im Uhrzeigersinn. |

## Felder

| Name | Beschreibung |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Die Seitendrehungen. |

### Siehe auch

* class [ViewOptions](../viewoptions)
* namensraum [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
