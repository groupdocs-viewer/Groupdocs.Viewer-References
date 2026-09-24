---
title: vertical_resolution property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The vertical resolution for generated images in dots per inch, used when rendering WordProcessing documents to PNG or JPEG formats only."
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/
is_root: false
weight: 2120
---


## vertical_resolution property

The vertical resolution for generated images in dots per inch, used when rendering WordProcessing documents to PNG or JPEG formats only.

Default value is 96 DPI.

Minimum possible value is 72 DPI and maximum possible value is 600 DPI. If a user-specified value is outside these limits, the nearest bound will be applied.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### See Also
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
