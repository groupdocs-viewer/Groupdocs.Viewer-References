---
title: "خاصية remove_unused_objects"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية تزيل الكائنات غير المستخدمة (المهجورة) من ملف PDF."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

الخاصية تزيل الكائنات غير المستخدمة (المهجورة) من ملف PDF.

هذه الكائنات موضوعة في مستند PDF لكنها غير مُشار إليها من قواميس الموارد لأي صفحة وبالتالي لا تُستخدم على الإطلاق. تفعيل هذه الخاصية (`True`) سيقلل حجم مستند PDF الناتج. بشكل افتراضي تكون معطلة (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### انظر أيضًا
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
