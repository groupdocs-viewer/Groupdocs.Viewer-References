---
title: "FontsToExclude"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Die Liste der Schriftartnamen, die vom HTML-Dokument ausgeschlossen werden sollen."
type: docs
weight: 40
url: /de/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---

## HtmlViewOptions.FontsToExclude property

Die Liste der Schriftartnamen, die vom HTML-Dokument ausgeschlossen werden sollen.

```csharp
public List<string> FontsToExclude { get; set; }
```

### Bemerkungen

Die Schriftarten, die dem HTML-Dokument hinzugefügt werden, erhöhen die Stabilität der Ausgabeansicht, vergrößern jedoch gleichzeitig die Größe des Renderings. Diese Option ermöglicht es Ihnen, ein Gleichgewicht zwischen Stabilität und Ausgabengröße zu finden. Geben Sie die Schriftartnamen an, die populär sind und auf den meisten Systemen installiert sind.

Bitte beachten Sie, dass diese Eigenschaft nur aktiv ist, wenn die [`ExcludeFonts`](../excludefonts)-Option deaktiviert ist.

Für Details und ein Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/exclude-fonts/).

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
