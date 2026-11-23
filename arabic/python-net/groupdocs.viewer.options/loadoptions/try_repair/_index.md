---
title: "خاصية try_repair"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "تمكن هذه الخاصية GroupDocs.Viewer من محاولة إصلاح الفساد الهيكلي في مستندات PDF."
type: docs
url: /ar/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

الخاصية تمكّن GroupDocs.Viewer من محاولة إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي False.

تُعالج هذه الميزة المشكلات التالية في مستند PDF:

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

### انظر أيضًا
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
