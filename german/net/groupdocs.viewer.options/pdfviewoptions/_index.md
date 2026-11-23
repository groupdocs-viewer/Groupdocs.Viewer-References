---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Rendern von Dokumenten im PDF-Format. Weitere Details siehe die Dokumentation https://docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /de/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Enthält Optionen zum Rendern von Dokumenten im PDF-Format. Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../pdfviewoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Die Ansichtseinstellungen für Archivdateien. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Die CAD-Zeichnungsansichtsoptionen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Legt die Standardschriftart für ein Dokument fest. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Die E-Mail-Nachrichten-Ansichtsoptionen. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Legt die Höhe eines Ausgabebildes fest (in Pixeln). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Legt die maximale Höhe eines Ausgabebildes fest (in Pixeln). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Legt die maximale Breite eines Ausgabebildes fest (in Pixeln). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Legt die Breite eines Ausgabebildes fest (in Pixeln). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Ansichtsoptionen für Mail‑Speicher‑Datendateien. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Die Microsoft Outlook-Datendateien-Ansichtsoptionen. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Reduziert die Größe der ausgegebenen PDF-Datei, indem Optimierungstechniken mit verschiedenen Optionen angewendet werden. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Die PDF-Dokument-Ansichtsoptionen. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Die Präsentationsdateien-Ansichtsoptionen. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Die Projektmanagement-Dateien-Ansichtsoptionen. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Deaktiviert das Rendern von Kommentaren, wenn auf `true` gesetzt. Standardmäßig ist `false` — alle Kommentare werden angezeigt. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiviert das Rendern versteckter Seiten. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiviert das Rendern von Notizen und Anmerkungen für einige Formate |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Legt die Sicherheitsoptionen des ausgegebenen PDF-Dokuments fest. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Die Tabellenkalkulationsdateien-Ansichtsoptionen. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Textdateien-Ansichtsoptionen. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Die Visio-Dateien-Ansichtsoptionen. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Das Textwasserzeichen, das auf jeder Seite angewendet wird. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Die Webdateien-Ansichtsoptionen. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Die Textverarbeitungsdateien-Ansichtsoptionen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
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
