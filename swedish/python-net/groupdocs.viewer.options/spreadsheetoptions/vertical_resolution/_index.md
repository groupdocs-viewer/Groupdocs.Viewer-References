---
title: "vertical_resolution egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Den vertikala upplösningen för genererade bilder i punkter per tum."
type: docs
url: /sv/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

Den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format.

Standardvärdet är 96 DPI. Minsta möjliga värde är 72 DPI; största möjliga värde är 600 DPI. Om ett användarspecificerat värde ligger utanför dessa gränser, kommer närmaste gränsvärde att tillämpas.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### Se även
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
