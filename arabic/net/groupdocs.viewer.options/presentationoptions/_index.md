---
title: "PresentationOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لعرض العروض التقديمية. لمزيد من التفاصيل راجع الوثائق https//docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /ar/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

يحتوي على خيارات لتصيير العروض التقديمية. للحصول على تفاصيل، راجع [الوثائق](https://docs.groupdocs.com/viewer/net/render-presentations/).

```csharp
public class PresentationOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PresentationOptions](presentationoptions)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | يفعل عرض العناصر النائبة في ترويسة وتذييل الشريحة. مُعطل بشكل افتراضي (`false`). ينطبق هذا الخيار على جميع أوضاع العرض الأربعة للعروض التقديمية: HTML، PDF، PNG، و JPEG. لا يُطبق عند عرض العرض التقديمي إلى تنسيق HTML/CSS نقي باستخدام [`RenderToPureHtml`](./rendertopurehtml). |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | يفعل وضع عرض HTML جديد لمستندات العرض التقديمي — في هذا الوضع تُعرض ملفات العرض إلى **pure HTML/CSS markup**، دون صور SVG. بشكل افتراضي يكون معطلاً (`false`) — يُستخدم عارض HTML القائم على SVG الحالي. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | دقة صور العرض التقديمي (لعرض إلى HTML/PDF فقط). |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
