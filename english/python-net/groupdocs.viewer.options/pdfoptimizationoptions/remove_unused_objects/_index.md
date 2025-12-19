---
title: remove_unused_objects property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 110
---

## remove_unused_objects property


Removes unused (orphaned) objects from a PDF file, which are placed in the PDF document, but are not referenced from resource dictionaries of any page and thus are not used at all. Activating this property (`true`) will decrease the output PDF document size. By default is disabled (`false`).
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
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions)
