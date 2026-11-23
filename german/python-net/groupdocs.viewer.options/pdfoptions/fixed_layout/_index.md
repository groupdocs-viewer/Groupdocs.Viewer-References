---
title: "fixed_layout‑Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Option für festes Layout ermöglicht das Rendern von PDF- und EPUB-Dokumenten zu HTML mit einem festen Layout."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

Die Option für festes Layout ermöglicht das Rendern von PDF- und EPUB-Dokumenten zu HTML mit einem festen Layout.

PDF‑ und EPUB‑Dokumente werden zunächst zu HTML mit einem festen Layout gerendert, um das Erscheinungsbild des Quelldokuments beizubehalten. Dieses feste Layout bedeutet, dass alle HTML‑Elemente präzise Positionen innerhalb eines Containers mit festgelegter Größe haben. Das Ändern der Größe des Browserfensters beeinflusst nicht die Position und Größe der Elemente im Dokument.

Diese Option ist nur beim Rendern zu HTML verfügbar. Der Standardwert ist `True`. Um mit einem fluiden Layout zu rendern, setze diese Eigenschaft auf `False`.

Beim Rendern zu fluidem Layout werden Bilder übersprungen. Verwende fluides Layout beim Rendern von PDF‑Dokumenten mit Textinhalt.

Für ein Codebeispiel siehe die Dokumentation.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Siehe auch
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
