---
title: ViewInfoOptions
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Bietet Optionen zum Abrufen von Informationen zur Ansicht.
type: docs
weight: 570
url: /de/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Bietet Optionen zum Abrufen von Informationen zur Ansicht.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Anzeigeoptionen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardschriftart, die verwendet wird, wenn eine bestimmte Schriftart, die im Dokument verwendet wird, nicht gefunden werden kann. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die Anzeigeoptionen für E-Mail-Nachrichten. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Gibt an, dass die Textextraktion aktiviert ist. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Bildhöhe (nur zum Rendern in PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für E-Mail-Speicherdatendateien. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Maximale Höhe des Ausgabebildes (nur zum Rendern in PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Maximale Breite des Ausgabebildes (nur zum Rendern in PNG/JPG) |
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
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Mit diesen Rendering-Optionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Webdokumenten anpassen. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Bildbreite (nur zum Rendern in PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Mit diesen Wiedergabeoptionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Word-Dokumenten anpassen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse zum Abrufen von Informationen zur Ansicht beim Rendern in HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse zum Abrufen von Informationen zur Ansicht beim Rendern in HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse zum Abrufen von Informationen zur Ansicht beim Rendern in JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse zum Abrufen von Informationen zur Ansicht beim Rendern in JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions)Klasse zum Abrufen von Informationen zur Ansicht beim Rendern in PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions)Klasse zum Abrufen von Informationen zur Ansicht beim Rendern in PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse basierend auf[`HtmlViewOptions`](../htmlviewoptions) Objekt. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse basierend auf[`JpgViewOptions`](../jpgviewoptions) Objekt. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initialisiert eine neue Instanz von[`ViewInfoOptions`](../viewinfooptions) Klasse basierend auf[`PngViewOptions`](../pngviewoptions) Objekt. |

### Siehe auch

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namensraum [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
