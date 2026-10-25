---
title: "DisableCopyProtection"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Schaltet den Kopierschutz für Inhalte beim Rendern zu HTML aus."
type: docs
weight: 30
url: /de/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

Schaltet den Kopierschutz für Inhalte beim Rendern zu HTML aus.

```csharp
public bool DisableCopyProtection { get; set; }
```

### Bemerkungen

Beim Rendern von PDF‑Dateien, die gegen das Kopieren von Text und Bildern nach HTML geschützt sind, fügt GroupDocs.Viewer dem HTML‑BODY‑Tag ein 'inert'-Attribut hinzu. Der Standardwert dieser Option ist `false`, was bedeutet, dass das 'intent'-Attribut nur hinzugefügt wird, wenn das PDF‑Dokument geschützt ist.

Für ein Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### Siehe auch

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
