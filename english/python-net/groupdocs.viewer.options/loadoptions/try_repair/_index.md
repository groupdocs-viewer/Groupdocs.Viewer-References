---
title: try_repair property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property enables GroupDocs.Viewer to attempt repairing structural corruption in PDF documents."
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

The property enables GroupDocs.Viewer to attempt repairing structural corruption in PDF documents. Default is False.

This feature addresses the following issues in a PDF document:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### See Also
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
