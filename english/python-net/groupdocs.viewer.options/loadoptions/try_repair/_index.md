---
title: try_repair property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 90
---

## try_repair property


When enabled GroupDocs.Viewer tries to repair structural corruption in PDF documents.
Default value is `false`.

### Remarks 


This feature addresses the following issues in a PDF document:
|
|
| Broken references within the document (incorrect object offsets in the Cross-reference list). |
| Missing critical elements like root object, page object, or page content. |
| Circular references (Form X-object referencing itself). |
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
* module [`groupdocs.viewer.options`](../../)
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions)
