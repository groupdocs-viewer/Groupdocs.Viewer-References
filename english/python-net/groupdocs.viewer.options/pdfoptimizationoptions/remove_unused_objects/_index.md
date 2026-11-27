---
title: remove_unused_objects property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property removes unused (orphaned) objects from a PDF file, decreasing the output size when set to True."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

The property removes unused (orphaned) objects from a PDF file, decreasing the output size when set to `True`.

Objects are placed in the PDF document but are not referenced from resource dictionaries of any page and thus are not used at all. By default the property is disabled (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### See Also
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
