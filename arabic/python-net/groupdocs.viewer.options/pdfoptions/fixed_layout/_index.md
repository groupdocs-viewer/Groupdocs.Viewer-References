---
title: "خاصية fixed_layout"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "خيار التخطيط الثابت يُتيح عرض مستندات PDF و EPUB إلى HTML بتخطيط ثابت."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

خيار التخطيط الثابت يُتيح عرض مستندات PDF و EPUB إلى HTML بتخطيط ثابت.

يتم في البداية تحويل مستندات PDF و EPUB إلى HTML باستخدام تخطيط ثابت للحفاظ على مظهر المستند الأصلي. يعني هذا التخطيط الثابت أن جميع عناصر HTML لها مواضع دقيقة داخل حاوية ذات حجم محدد. لا يؤثر تغيير حجم نافذة المتصفح على موضع وحجم العناصر في المستند.

هذا الخيار متاح فقط عند التحويل إلى HTML. القيمة الافتراضية هي `True`. لتوليد تخطيط مرن، اضبط هذه الخاصية على `False`.

عند التحويل إلى تخطيط مرن، يتم تخطي الصور. استخدم التخطيط المرن عند تحويل مستندات PDF التي تحتوي على نص.

للحصول على مثال شفرة، راجع الوثائق.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### انظر أيضًا
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
