---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Abrufen von Informationen zur Ansicht."
type: docs
weight: 580
url: /de/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Enthält Optionen zum Abrufen von Informationen zur Ansicht.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Ansichtseinstellungen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Legt die Standardschriftart für ein Dokument fest. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die E-Mail-Nachrichten-Ansichtsoptionen. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Aktiviert die Textextraktion. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Die Höhe des Ausgabebildes (in Pixeln, nur für die Darstellung als PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für Mail‑Speicher‑Datendateien. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Legt die maximale Höhe eines Ausgabebildes fest (in Pixeln, nur für die Darstellung als PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Legt die maximale Breite eines Ausgabebildes fest (in Pixeln, nur für die Darstellung als PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Die Microsoft Outlook-Datendateien-Ansichtsoptionen. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Die PDF-Dokument-Ansichtsoptionen. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Die Präsentationsdateien-Ansichtsoptionen. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Die Projektmanagement-Dateien-Ansichtsoptionen. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Deaktiviert das Rendern von Kommentaren, wenn auf `true` gesetzt. Standardmäßig ist `false` — alle Kommentare werden angezeigt. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiviert das Rendern versteckter Seiten. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiviert das Rendern von Notizen und Anmerkungen für einige Formate |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Die Tabellenkalkulationsdateien-Ansichtsoptionen. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Textdateien-Ansichtsoptionen. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Die Visio-Dateien-Ansichtsoptionen. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Die Webdateien-Ansichtsoptionen. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Die Breite des Ausgabebildes (in Pixeln, nur für die Darstellung als PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Die Textverarbeitungsdateien-Ansichtsoptionen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in HTML abzurufen. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in HTML abzurufen. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in JPG abzurufen. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in JPG abzurufen. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in PDF abzurufen. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in PNG abzurufen. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions), um Informationen zur Ansicht beim Rendern in PNG abzurufen. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions) basierend auf dem Objekt [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions) basierend auf dem Objekt [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions) basierend auf dem Objekt [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initialisiert eine Instanz der Klasse [`ViewInfoOptions`](../viewinfooptions) basierend auf dem Objekt [`PngViewOptions`](../pngviewoptions). |

### Siehe auch

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
