---
title: "RemoveComments"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعطل عرض التعليقات عندما يتم ضبطه على true. بشكل افتراضي يكون false وتُعرض جميع التعليقات."
type: docs
weight: 100
url: /ar/net/groupdocs.viewer.options/baseviewoptions/removecomments/
---

## BaseViewOptions.RemoveComments property

يعطل عرض التعليقات عند تعيينه إلى `true`. بشكل افتراضي يكون `false` — جميع التعليقات تُعرض.

```csharp
public bool RemoveComments { get; set; }
```

### ملاحظات

قد تحتوي بعض صيغ المستندات مثل PDF وWordProcessing على تعليقات. بشكل افتراضي يقوم GroupDocs.Viewer بعرضها. عند ضبط هذا الخيار على `true` قد يتم استبعاد التعليقات من المستند الناتج.

هذا الخيار يستبدل الخاصية القديمة 'RenderComments'.

### انظر أيضًا

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
