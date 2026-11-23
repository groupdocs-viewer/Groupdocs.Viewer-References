---
title: "horizontal_resolution Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/
is_root: false
weight: 2050
---


## horizontal_resolution property

Die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet.

Standardwert ist 96 DPI. Der minimal mögliche Wert beträgt 72 DPI, der maximal mögliche Wert 600 DPI. Wenn ein vom Benutzer angegebener Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert angewendet.

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
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
