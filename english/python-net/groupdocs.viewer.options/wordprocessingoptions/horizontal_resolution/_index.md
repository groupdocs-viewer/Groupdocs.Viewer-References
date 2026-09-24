---
title: horizontal_resolution property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The horizontal resolution for generated images in dots per inch."
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

The horizontal resolution for generated images in dots per inch. This option is used when rendering WordProcessing documents to PNG or JPEG formats only.

Default value is 96 DPI. Minimum possible value is 72 DPI; maximum possible value is 600 DPI. If a user‑specified value is outside these limits, the nearest bound (minimum or maximum) will be applied.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### See Also
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
