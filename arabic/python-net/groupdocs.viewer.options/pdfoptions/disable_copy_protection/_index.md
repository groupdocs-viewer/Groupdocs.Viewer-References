---
title: "خاصية disable_copy_protection"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية تُعطل حماية نسخ المحتوى عند العرض إلى HTML."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

الخاصية تُعطل حماية نسخ المحتوى عند العرض إلى HTML.

عند تحويل ملفات PDF مع حماية ضد نسخ النصوص والصور إلى HTML، يضيف GroupDocs.Viewer سمة HTML `inert` إلى وسم BODY في HTML. القيمة الافتراضية هي `False`، مما يعني أن سمة `inert` تُضاف فقط إذا كان مستند PDF محميًا.

للحصول على مثال شفرة، راجع الوثائق.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### انظر أيضًا
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
