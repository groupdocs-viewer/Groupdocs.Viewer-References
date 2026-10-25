---
title: "LoadOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen, die zum Öffnen der Datei verwendet werden. Weitere Details siehe diese Seite https://docs.groupdocs.com/viewer/net/loading/ und deren Unterseiten."
type: docs
weight: 360
url: /de/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Enthält Optionen, die zum Öffnen der Datei verwendet werden. Weitere Details finden Sie auf dieser [Seite](https://docs.groupdocs.com/viewer/net/loading/) und deren Unterseiten.

```csharp
public class LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Initialisiert eine Instanz der Klasse [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Initialisiert eine Instanz der Klasse [`LoadOptions`](../loadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Aktiviert die Zeichencodierungserkennung für die Dateien [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) und [`TSV`](../../groupdocs.viewer/filetype/tsv). |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Legt die beim Öffnen von textbasierten Dateien oder E-Mail-Nachrichten wie [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) und [`MSG`](../../groupdocs.viewer/filetype/msg) verwendete Codierung fest. Der Standardwert ist UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Legt den Typ der zu öffnenden Datei fest. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Legt das Passwort zum Öffnen einer verschlüsselten Datei fest. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Legt das Timeout zum Laden externer Ressourcen fest. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | Deaktiviert das Laden aller externen Ressourcen wie Bilder, außer [`WhitelistedResources`](./whitelistedresources). |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | Wenn aktiviert, versucht GroupDocs.Viewer strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | Die Liste der URL‑Fragmente, die externen Ressourcen entsprechen und geladen werden sollen, wenn [`SkipExternalResources`](./skipexternalresources) auf `true` gesetzt ist. |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
