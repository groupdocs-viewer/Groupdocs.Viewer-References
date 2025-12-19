---
title: remove_unused_streams property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/
is_root: false
weight: 120
---

## remove_unused_streams property


Removes unused (orphaned) streams from a PDF file, which are still referenced from the resource dictionary of the page, but actually are never used in the page contents. By default is disabled (`false`), its enabling (`true`) will decrease the output PDF document size.
### Definition:
```python
@property
def remove_unused_streams(self):
    ...
@remove_unused_streams.setter
def remove_unused_streams(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions)
