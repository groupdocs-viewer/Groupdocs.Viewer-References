---
title: "layout_name egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Namnet på den specifika layouten att rendera."
type: docs
url: /sv/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

Namnet på den specifika layouten som ska renderas. Layoutnamnet är skiftlägeskänsligt.

Det här alternativet är endast tillgängligt för CAD-ritningar som stödjer layouter: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), och [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); Som standard renderas endast Modellen.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### Se även
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
