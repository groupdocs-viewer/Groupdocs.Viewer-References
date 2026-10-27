---
title: "horizontal_resolution Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll."
type: docs
url: /de/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

Die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet.

Standardwert ist 96 DPI. Der minimal mögliche Wert beträgt 72 DPI; der maximal mögliche Wert 600 DPI. Liegt ein benutzerdefinierter Wert außerhalb dieser Grenzen, wird die nächstliegende Grenze (Minimum oder Maximum) angewendet.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Siehe auch
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
