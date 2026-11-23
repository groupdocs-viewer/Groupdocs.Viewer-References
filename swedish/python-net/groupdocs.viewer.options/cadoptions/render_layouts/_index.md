---
title: "render_layouts egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Flaggan som indikerar om layouter från CAD-dokumentet ska renderas."
type: docs
url: /sv/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

Flaggan som indikerar om layouter från CAD-dokumentet ska renderas.

Det här alternativet är endast tillgängligt för CAD-ritningar som stödjer layouter [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), och [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). Som standard renderas endast Modellen.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### Se även
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
