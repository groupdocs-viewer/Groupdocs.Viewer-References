---
title: "vertical_resolution eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De verticale resolutie voor gegenereerde afbeeldingen in dots per inch."
type: docs
url: /nl/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

De verticale resolutie voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van spreadsheets naar PNG- of JPEG-formaten.

Standaardwaarde is 96 DPI. Minimum mogelijke waarde is 72 DPI; maximum mogelijke waarde is 600 DPI. Als een door de gebruiker opgegeven waarde buiten deze limieten valt, wordt de dichtstbijzijnde grens toegepast.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### Zie ook
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
