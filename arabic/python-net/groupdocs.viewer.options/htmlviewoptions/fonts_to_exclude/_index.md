---
title: "خاصية fonts_to_exclude"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "قائمة أسماء الخطوط لاستبعادها من مستند HTML."
type: docs
url: /ar/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

قائمة أسماء الخطوط لاستبعادها من مستند HTML.

الخطوط التي تُضاف إلى مستند HTML تحسن استقرار عرض الإخراج، وفي الوقت نفسه تزيد من حجم نتيجة التصيير. يتيح لك هذا الخيار الموازنة بين الاستقرار وحجم الإخراج. قم بتضمين أسماء الخطوط الشائعة والمثبتة في معظم الأنظمة.

يرجى ملاحظة، هذه الخاصية نشطة فقط عندما يكون خيار [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) معطلاً.

للحصول على تفاصيل ومثال على الشيفرة، راجع الوثائق.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### انظر أيضًا
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
