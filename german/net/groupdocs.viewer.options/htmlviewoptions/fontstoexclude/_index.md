---
title: FontsToExclude
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Die Liste der Schriftartnamen die aus dem HTMLDokument ausgeschlossen werden sollen.
type: docs
weight: 40
url: /de/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---
## HtmlViewOptions.FontsToExclude property

Die Liste der Schriftartnamen, die aus dem HTML-Dokument ausgeschlossen werden sollen.

```csharp
public List<string> FontsToExclude { get; set; }
```

### Bemerkungen

Diese Option wird nur für Präsentationen unterstützt. Die dem HTML-Dokument hinzugefügten Schriftarten verbessern die Stabilität der Ausgabeansicht, gleichzeitig erhöhen sie die Größe des Rendering-Ergebnisses. Diese Option lässt Sie einen Kompromiss zwischen Stabilität und Ausgabegröße finden. Schließen Sie die Schriftnamen ein, die beliebt und auf den meisten Systemen installiert sind. Bitte beachten Sie, dass diese Eigenschaft nur aktiv ist, wenn[`ExcludeFonts`](../excludefonts) Optionen sind deaktiviert.

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namensraum [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->