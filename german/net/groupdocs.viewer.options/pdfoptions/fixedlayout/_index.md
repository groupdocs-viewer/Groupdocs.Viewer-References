---
title: "FixedLayout"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Ermöglicht das Rendern von PDF- und EPUB-Dokumenten zu HTML mit festem Layout."
type: docs
weight: 70
url: /de/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

Ermöglicht das Rendern von PDF- und EPUB-Dokumenten zu HTML mit festem Layout.

```csharp
public bool FixedLayout { get; set; }
```

### Bemerkungen

PDF‑ und EPUB‑Dokumente werden zunächst mit einem festen Layout nach HTML gerendert, um das Erscheinungsbild des Ausgangsdokuments beizubehalten. Dieses feste Layout bedeutet, dass alle HTML‑Elemente präzise Positionen innerhalb eines Containers mit fester Größe haben. Das Ändern der Größe des Browser‑Fensters beeinflusst nicht die Position und Größe der Elemente im Dokument.

Diese Option ist nur beim Rendern nach HTML verfügbar. Der Standardwert ist `true`. Um mit einem fluiden Layout zu rendern, setzen Sie diese Eigenschaft auf `false`.

Beim Rendern mit fluidem Layout werden Bilder übersprungen. Verwenden Sie ein fluides Layout beim Rendern von PDF‑Dokumenten mit Textinhalt.

Für ein Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### Siehe auch

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
