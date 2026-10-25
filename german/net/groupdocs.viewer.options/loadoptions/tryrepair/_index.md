---
title: "TryRepair"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Wenn aktiviert, versucht GroupDocs.Viewer strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist false."
type: docs
weight: 80
url: /de/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

Wenn aktiviert, versucht GroupDocs.Viewer strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist `false`.

```csharp
public bool TryRepair { get; set; }
```

### Bemerkungen

Diese Funktion behebt die folgenden Probleme in einem PDF-Dokument:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### Siehe auch

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
