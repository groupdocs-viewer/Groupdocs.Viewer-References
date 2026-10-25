---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Rendern von Word-Dokumenten. Weitere Details siehe die Dokumentation https://docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /de/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Enthält Optionen zum Rendern von Word-Dokumenten. Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Enthält Optionen zum Rendern von Textverarbeitungsdokumenten. Weitere Details siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Legt den unteren Rand einer Seite fest. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Diese Option aktiviert Kerning und andere OpenType‑Funktionen beim Rendern von Arabisch, Hebräisch, indisch‑lateinbasierten oder kyrillisch‑basierten Skripten. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Liest oder setzt die horizontale Auflösung für erzeugte Bilder in DPI (dots per inch). Diese Option wird nur beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Legt den linken Rand einer Seite fest. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Ermöglicht das erzwungene Anwenden der Seitennummerierung für das geladene WordProcessing‑Dokument. Standardmäßig ist NotApply — das Dokument bleibt unverändert. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | Die Größe der Ausgabeseite. Der Standardwert ist Unspecified, was bedeutet, dass eine in den Seiteneinstellungen (Page Setup) festgelegte Seitengröße verwendet wird. Beim Rendern von HTM‑ und HTML‑Dateien wird die Standardseitengröße auf Letter 792 × 612 Punkte gesetzt. Infolgedessen passt ein Teil des Inhalts möglicherweise nicht in den Seitenrahmen. Legen Sie eine größere Seitengröße fest, z. B. A3, um den Inhalt zu passen. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Aktiviert das Rendern von nachverfolgten Änderungen (Revisionen). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Legt den rechten Rand einer Seite fest. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Legt den oberen Rand einer Seite fest. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | Beim Rendern zu HTML oder PDF können Sie diese Option auf `true` setzen, um die Navigation im Inhaltsverzeichnis zu deaktivieren. Beim HTML-Rendering werden `a`‑Tags mit relativen Links durch `span`‑Tags ersetzt, wodurch die Funktionalität entfernt, aber das visuelle Erscheinungsbild erhalten bleibt. Beim PDF-Rendering wird das Inhaltsverzeichnis als reiner Text ohne Links zu Dokumentabschnitten gerendert. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Liest oder setzt einen Wert, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Formate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. Der Standardwert für diese Eigenschaft ist `true` — Felder werden vor dem Speichern aktualisiert. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Liest oder setzt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von WordProcessing‑Dokumenten in die Formate PNG oder JPEG verwendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Erstellt und gibt eine vollständige tiefe Kopie dieser Optionen zurück |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Bestimmt, ob die angegebene Instanz von [`WordProcessingOptions`](../wordprocessingoptions) gleich dieser ist |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
