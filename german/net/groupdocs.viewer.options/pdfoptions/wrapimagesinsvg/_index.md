---
title: "WrapImagesInSvg"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Ermöglicht das Einbetten jedes Bildes im HTML‑Ausgabedokument in ein SVG‑Tag, um die Ausgabequalität zu verbessern."
type: docs
weight: 110
url: /de/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

Ermöglicht das Einbetten jedes Bildes im HTML‑Ausgabedokument in ein SVG‑Tag, um die Ausgabequalität zu verbessern.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### Bemerkungen

Standardmäßig werden beim Rendern von PDF- und Page‑Layout‑Dateien zu HTML alle Bilder als ein PNG‑Bild gerendert. Das gerenderte PNG‑Bild wird als Hintergrund für das Ausgabedokument HTML verwendet.

Diese Option ist verfügbar, wenn [PDF- und Page‑Layout‑Dateiformate](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) zu HTML mit eingebetteten und externen Ressourcen gerendert werden. Sie ermöglicht das Einbetten jedes Bildes im Ausgabedokument HTML in ein SVG‑Tag. Der Standardwert ist `false`.

Für ein Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).

### Siehe auch

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
