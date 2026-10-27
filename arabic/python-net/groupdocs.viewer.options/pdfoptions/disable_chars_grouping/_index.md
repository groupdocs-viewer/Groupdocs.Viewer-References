---
title: "خاصية disable_chars_grouping"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية تُعطل تجميع الرموز لتحديد موضع الرموز بدقة أثناء عرض الصفحة."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

الخاصية تُعطل تجميع الرموز لتحديد موضع الرموز بدقة أثناء عرض الصفحة.

عند تحويل ملفات PDF، يقوم GroupDocs.Viewer بتجميع الأحرف الفردية إلى كلمات لتحسين أداء العرض. إذا كان مستندك يحتوي على رموز هيروغليفية أو رموز خاصة، قد ترغب في منع تجميع الأحرف لضمان تخطيط أكثر دقة. القيمة الافتراضية هي False.

للحصول على مثال على الشيفرة، راجع الوثائق.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### انظر أيضًا
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
