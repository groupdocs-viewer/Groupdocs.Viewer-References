---
title: "wrap_images_in_svg Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft, die das Einbetten jedes Bildes im HTML‑Ausgabedokument in ein SVG‑Tag ermöglicht, um die Ausgabequalität zu verbessern."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

Die Eigenschaft, die das Einbetten jedes Bildes im HTML‑Ausgabedokument in ein SVG‑Tag ermöglicht, um die Ausgabequalität zu verbessern.

Standardmäßig werden beim Rendern von PDF‑ und Page‑Layout‑Dateien nach HTML alle Bilder als ein PNG‑Bild gerendert. Das gerenderte PNG‑Bild wird als Hintergrund für das ausgegebene HTML‑Dokument verwendet.

Diese Option ist verfügbar, wenn PDF‑ und Page‑Layout‑Dateiformate nach HTML mit eingebetteten und externen Ressourcen gerendert werden. Sie ermöglicht das Einbetten jedes Bildes im ausgegebenen HTML‑Dokument in ein SVG‑Tag. Der Standardwert ist False.

Für ein Codebeispiel siehe die Dokumentation.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Siehe auch
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
