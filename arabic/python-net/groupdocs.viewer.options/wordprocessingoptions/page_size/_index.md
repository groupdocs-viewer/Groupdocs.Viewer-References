---
title: "خاصية page_size"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "حجم الصفحة الناتجة."
type: docs
url: /ar/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

حجم الصفحة الناتجة.

القيمة الافتراضية هي `PageSize.Unspecified`، مما يعني أنه يتم استخدام حجم الصفحة المحدد في إعدادات الصفحة (Page Setup).

عند تصوير ملفات HTM و HTML يتم تعيين حجم الصفحة الافتراضي إلى Letter 792 × 612 نقطة.

نتيجة لذلك، قد لا يتناسب بعض المحتوى مع إطار الصفحة.

قم بتعيين حجم صفحة أكبر، على سبيل المثال `PageSize.A3` لتناسب المحتوى.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### انظر أيضًا
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
