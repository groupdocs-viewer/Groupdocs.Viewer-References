---
title: remove_unused_streams property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property removes unused (orphaned) streams from a PDF file, which are still referenced from the resource dictionary of the page but never used in the page contents."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/
is_root: false
weight: 2100
---


## remove_unused_streams property

The property removes unused (orphaned) streams from a PDF file, which are still referenced from the resource dictionary of the page but never used in the page contents.

By default it is disabled (`False`); setting it to `True` decreases the output PDF document size.

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
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
