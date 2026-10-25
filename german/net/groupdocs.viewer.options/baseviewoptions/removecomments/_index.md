---
title: "RemoveComments"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Deaktiviert das Rendern von Kommentaren, wenn auf true gesetzt. Standardmäßig ist false, alle Kommentare werden angezeigt."
type: docs
weight: 100
url: /de/net/groupdocs.viewer.options/baseviewoptions/removecomments/
---

## BaseViewOptions.RemoveComments property

Deaktiviert das Rendern von Kommentaren, wenn auf `true` gesetzt. Standardmäßig ist `false` — alle Kommentare werden angezeigt.

```csharp
public bool RemoveComments { get; set; }
```

### Bemerkungen

Einige Dokumentformate wie PDF und WordProcessing können Kommentare enthalten. Standardmäßig rendert GroupDocs.Viewer sie. Wenn diese Option auf `true` gesetzt ist, können die Kommentare aus dem resultierenden Dokument ausgeschlossen werden.

Diese Option ersetzt die veraltete Eigenschaft 'RenderComments'.

### Siehe auch

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
