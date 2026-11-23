---
title: "خاصية wrap_images_in_svg"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية التي تُتيح تغليف كل صورة في مستند HTML الناتج داخل وسم SVG لتحسين جودة الإخراج."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

الخاصية التي تُتيح تغليف كل صورة في مستند HTML الناتج داخل وسم SVG لتحسين جودة الإخراج.

بشكل افتراضي، عند تحويل ملفات PDF وPage Layout إلى HTML، يتم تحويل جميع الصور إلى صورة PNG واحدة. تُستخدم صورة PNG المُحوَّلة كخلفية للمستند HTML الناتج.

هذا الخيار متاح عند تحويل صيغ ملفات PDF وPage Layout إلى HTML مع موارد مضمَّنة وخارجية. يتيح تغليف كل صورة في المستند HTML الناتج بوسم SVG. القيمة الافتراضية هي False.

للحصول على مثال شفرة، راجع الوثائق.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### انظر أيضًا
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
