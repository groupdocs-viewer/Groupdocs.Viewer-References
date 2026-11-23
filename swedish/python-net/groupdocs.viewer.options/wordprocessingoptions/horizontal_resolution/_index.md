---
title: "horizontal_resolution egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Den horisontella upplösningen för genererade bilder i punkter per tum."
type: docs
url: /sv/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

Den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av WordProcessing‑dokument till PNG‑ eller JPEG‑format.

Standardvärdet är 96 DPI. Minsta möjliga värde är 72 DPI; största möjliga värde är 600 DPI. Om ett användarspecificerat värde ligger utanför dessa gränser kommer närmaste gränsvärde (minimum eller maximum) att tillämpas.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Se även
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
