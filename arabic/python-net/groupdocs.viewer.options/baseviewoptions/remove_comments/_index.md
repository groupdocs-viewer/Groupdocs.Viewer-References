---
title: "خاصية remove_comments"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "تقوم الخاصية بتعطيل عرض التعليقات عند تعيينها إلى True."
type: docs
url: /ar/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

الخاصية تعطل عرض التعليقات عندما تكون مضبوطة على True. بشكل افتراضي تكون False، لذا تُعرض جميع التعليقات.

قد تحتوي بعض صيغ المستندات مثل PDF وWordProcessing على تعليقات. بشكل افتراضي، يقوم GroupDocs.Viewer بعرضها. عند تعيين هذا الخيار إلى True، يمكن استبعاد التعليقات من المستند الناتج.

هذا الخيار يستبدل الخاصية القديمة `RenderComments`.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### انظر أيضًا
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
