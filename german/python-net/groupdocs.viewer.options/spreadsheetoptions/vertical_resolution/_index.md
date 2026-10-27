---
title: "vertical_resolution Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

Die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet.

Der Standardwert beträgt 96 DPI. Der minimal mögliche Wert beträgt 72 DPI; der maximal mögliche Wert beträgt 600 DPI. Wenn ein benutzerdefinierter Wert außerhalb dieser Grenzen liegt, wird die nächstliegende Grenze angewendet.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### Siehe auch
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
