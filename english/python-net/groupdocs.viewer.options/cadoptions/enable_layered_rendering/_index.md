---
title: enable_layered_rendering property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The flag that enables layer-oriented rendering of CAD drawings to HTML format; when True, each layer is rendered with its ID and objects sharing the same layer name are grouped into top-level groups…"
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/enable_layered_rendering/
is_root: false
weight: 2020
---


## enable_layered_rendering property

The flag that enables layer-oriented rendering of CAD drawings to HTML format; when True, each layer is rendered with its ID and objects sharing the same layer name are grouped into top-level groups with an `id` tag set to the layer name, and it is disabled (False) by default.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
