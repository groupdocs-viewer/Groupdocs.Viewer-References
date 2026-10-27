---
title: "خاصية horizontal_resolution"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة."
type: docs
url: /ar/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

الدقة الأفقية للصور المُولَّدة بالنقطة لكل بوصة. يُستخدم هذا الخيار عند تصيير مستندات WordProcessing إلى صيغ PNG أو JPEG فقط.

القيمة الافتراضية هي 96 DPI. القيمة الدنيا الممكنة هي 72 DPI؛ والقيمة العليا الممكنة هي 600 DPI. إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق أقرب حد (الحد الأدنى أو الأعلى).

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### انظر أيضًا
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
