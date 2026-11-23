---
title: "render_notes egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen möjliggör rendering av anteckningar och annotationer för vissa format."
type: docs
url: /sv/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

Egenskapen möjliggör rendering av anteckningar och annotationer för vissa format.

Vissa format, såsom presentationer eller Microsoft-projektfiler, kan innehålla anteckningar. Dessutom kan PDF-filer ha popup-anteckningar (ballongtips) som är dolda som standard och endast synliga i en PDF-visare när muspekaren hålls över dem. Som standard renderar GroupDocs.Viewer inte sådana anteckningar och annotationer (`False`). För att göra detta, sätt denna egenskap till `True`.

För ett kodexempel, se dokumentationen.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Se även
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
