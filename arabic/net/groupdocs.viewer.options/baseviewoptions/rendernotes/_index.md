---
title: "RenderNotes"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يفعل عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ"
type: docs
weight: 120
url: /ar/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

يفعل عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ

```csharp
public bool RenderNotes { get; set; }
```

### ملاحظات

قد تحتوي بعض الصيغ، مثل العروض التقديمية أو ملفات Microsoft Project، على ملاحظات. كذلك، قد تحتوي ملفات PDF على تعليقات توضيحية منبثقة (تلميحات بالون)، تكون مخفية بشكل افتراضي وتظهر في عارض PDF فقط عند توجيه مؤشر الفأرة إليها. بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض هذه الملاحظات والتعليقات (`false`). للقيام بذلك، اضبط هذه الخاصية على `true`.

لمثال الكود، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes).

### انظر أيضًا

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
