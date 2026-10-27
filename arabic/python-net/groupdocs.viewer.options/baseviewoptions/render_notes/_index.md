---
title: "خاصية render_notes"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية تمكّن عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ."
type: docs
url: /ar/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

الخاصية تمكّن عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ.

بعض الصيغ، مثل العروض التقديمية أو ملفات Microsoft Project، قد تحتوي على ملاحظات. أيضًا، قد تحتوي ملفات PDF على تعليقات منبثقة (تلميحات بالبالون) تكون مخفية بشكل افتراضي وتظهر في عارض PDF فقط عند توجيه مؤشر الفأرة إليها. بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض هذه الملاحظات والتعليقات (`False`). للقيام بذلك، اضبط هذه الخاصية على `True`.

للحصول على مثال شفرة، راجع الوثائق.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### انظر أيضًا
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
