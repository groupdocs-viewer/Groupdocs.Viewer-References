---
title: PngViewOptions
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Bietet Optionen zum Rendern von Dokumenten im PNGFormat.
type: docs
weight: 440
url: /de/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

Bietet Optionen zum Rendern von Dokumenten im PNG-Format.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Initialisiert eine neue Instanz von[`PngViewOptions`](../pngviewoptions) Klasse. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Initialisiert eine neue Instanz von[`PngViewOptions`](../pngviewoptions) Klasse. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Initialisiert eine neue Instanz von[`PngViewOptions`](../pngviewoptions) Klasse. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Initialisiert eine neue Instanz von[`PngViewOptions`](../pngviewoptions) Klasse. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz von[`PngViewOptions`](../pngviewoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Anzeigeoptionen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardschriftart, die verwendet wird, wenn eine bestimmte Schriftart, die im Dokument verwendet wird, nicht gefunden werden kann. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die Anzeigeoptionen für E-Mail-Nachrichten. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Aktiviert die Textextraktion. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Die Höhe eines Ausgabebildes in Pixel. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für E-Mail-Speicherdatendateien. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Maximale Höhe eines Ausgabebildes in Pixel. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Maximale Breite eines Ausgabebildes in Pixel. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Die Ansichtsoptionen für MS Outlook-Datendateien. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Die Anzeigeoptionen für PDF-Dokumente. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Die Anzeigeoptionen für Präsentationsverarbeitungsdokumente. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Die Ansichtsoptionen für Projektverwaltungsdateien. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Aktiviert das Rendern von Kommentaren. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiviert das Rendern versteckter Seiten. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiviert das Rendern von Notizen. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Die Anzeigeoptionen für Tabellenkalkulationsdateien. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Optionen zum Aufteilen von Textdateien in Seiten. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Die Optionen für die Ansicht von Visio-Dateien, die Dokumente verarbeiten. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Das auf jede Seite angewendete Textwasserzeichen. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Mit diesen Rendering-Optionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Webdokumenten anpassen. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | Die Breite des Ausgabebildes in Pixel. |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namensraum [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
