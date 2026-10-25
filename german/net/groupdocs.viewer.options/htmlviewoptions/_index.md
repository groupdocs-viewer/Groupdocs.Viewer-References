---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Rendern von Dokumenten im HTML-Format. Weitere Details siehe das Thema https://docs.groupdocs.com/viewer/net/renderingtohtml/ und dessen Unterseiten."
type: docs
weight: 320
url: /de/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Enthält Optionen zum Rendern von Dokumenten im HTML-Format. Weitere Details finden Sie im [Thema](https://docs.groupdocs.com/viewer/net/rendering-to-html/) und dessen Unterseiten.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Ansichtseinstellungen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Legt die Standardschriftart für ein Dokument fest. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die E-Mail-Nachrichten-Ansichtsoptionen. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Deaktiviert das Hinzufügen von Schriftarten zum HTML-Dokument. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Die Liste der Schriftartnamen, die vom HTML-Dokument ausgeschlossen werden sollen. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Aktiviert die Optimierung des ausgegebenen HTML für den Druck. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Die Höhe eines Ausgabebildes (in Pixel). Die Eigenschaft ist nur beim Konvertieren eines einzelnen Bildes zu HTML verfügbar. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Maximale Höhe eines Ausgabebildes (in Pixel). Die Eigenschaft ist nur beim Konvertieren eines einzelnen Bildes zu HTML verfügbar. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Maximale Breite eines Ausgabebildes (in Pixel). Die Eigenschaft ist nur beim Konvertieren eines einzelnen Bildes zu HTML verfügbar. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Die Breite des Ausgabebildes (in Pixel). Die Eigenschaft ist nur beim Konvertieren eines einzelnen Bildes zu HTML verfügbar. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für Mail‑Speicher‑Datendateien. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Aktiviert die Minimierung von HTML-Inhalten und HTML-Ressourcen. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Die Microsoft Outlook-Datendateien-Ansichtsoptionen. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Die PDF-Dokument-Ansichtsoptionen. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Die Präsentationsdateien-Ansichtsoptionen. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Die Projektmanagement-Dateien-Ansichtsoptionen. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Deaktiviert das Rendern von Kommentaren, wenn auf `true` gesetzt. Standardmäßig ist `false` — alle Kommentare werden angezeigt. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Ermöglicht das Entfernen des JavaScript-Quellcodes aus den Links in resultierenden HTML-Dokumenten, wenn Eingabedokumente gerendert werden, die Skripte enthalten. Standardmäßig ist dies aktiviert (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiviert das Rendern versteckter Seiten. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiviert das Rendern von Notizen und Anmerkungen für einige Formate |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Aktiviert responsives Rendering. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Aktiviert das Rendern eines gesamten Dokuments in eine einzige HTML-Datei. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Die Tabellenkalkulationsdateien-Ansichtsoptionen. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Textdateien-Ansichtsoptionen. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Die Visio-Dateien-Ansichtsoptionen. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Das Textwasserzeichen, das auf jeder Seite angewendet wird. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Die Webdateien-Ansichtsoptionen. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Die Textverarbeitungsdateien-Ansichtsoptionen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse zum Rendern in HTML mit externen Ressourcen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse zum Rendern in HTML mit externen Ressourcen. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initialisiert eine Instanz der [`HtmlViewOptions`](../htmlviewoptions)-Klasse zum Rendern in HTML mit externen Ressourcen. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Wendet die Drehung im Uhrzeigersinn auf eine Seite an. |

## Felder

| Name | Beschreibung |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Die Seitenrotation. |

### Siehe auch

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
