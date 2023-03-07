---
title: HtmlViewOptions
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Bietet Optionen zum Rendern von Dokumenten im HTMLFormat.
type: docs
weight: 330
url: /de/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Bietet Optionen zum Rendern von Dokumenten im HTML-Format.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Anzeigeoptionen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardschriftart, die verwendet wird, wenn eine bestimmte Schriftart, die im Dokument verwendet wird, nicht gefunden werden kann. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die Anzeigeoptionen für E-Mail-Nachrichten. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Wenn aktiviert, wird das Hinzufügen von Schriftarten zum HTML-Dokument verhindert. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Die Liste der Schriftartnamen, die aus dem HTML-Dokument ausgeschlossen werden sollen. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Gibt an, ob Ausgabe-HTML für den Druck optimiert werden soll. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Die Höhe eines Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Maximale Höhe eines Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Maximale Breite eines Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Die Breite des Ausgabebildes in Pixel. (Nur beim Konvertieren eines einzelnen Bildes in HTML) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für E-Mail-Speicherdatendateien. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Aktiviert die Minimierung von HTML-Inhalten und HTML-Ressourcen. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Die Ansichtsoptionen für MS Outlook-Datendateien. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Die Anzeigeoptionen für PDF-Dokumente. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Die Anzeigeoptionen für Präsentationsverarbeitungsdokumente. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Die Ansichtsoptionen für Projektverwaltungsdateien. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Aktiviert das Rendern von Kommentaren. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiviert das Rendern versteckter Seiten. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiviert das Rendern von Notizen. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Aktiviert responsives Rendering; Responsive Webseiten werden auf Geräten mit unterschiedlicher Bildschirmgröße gut gerendert. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Ermöglicht das Rendern eines gesamten Dokuments in eine HTML-Datei. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Die Anzeigeoptionen für Tabellenkalkulationsdateien. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Optionen zum Aufteilen von Textdateien in Seiten. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Die Optionen für die Ansicht von Visio-Dateien, die Dokumente verarbeiten. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Das auf jede Seite angewendete Textwasserzeichen. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Mit diesen Rendering-Optionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Webdokumenten anpassen. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Mit diesen Wiedergabeoptionen können Sie das Erscheinungsbild von der HTML/PDF/PNG/JPEG-Ausgabe beim Rendern von Word-Dokumenten anpassen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse zum Rendern in HTML mit eingebetteten Ressourcen. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse zum Rendern in HTML mit eingebetteten Ressourcen. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse zum Rendern in HTML mit eingebetteten Ressourcen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initialisiert eine neue Instanz von[`HtmlViewOptions`](../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen. |
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
