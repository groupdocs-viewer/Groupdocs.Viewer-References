---
title: "op_Explicit"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يقوم بتحويل صريح من Argb32Colorgroupdocs.viewer.drawing/argb32color 32 بت إلى Rgb24Colorgroupdocs.viewer.drawing/rgb24color 24 بت. سيتم فقدان قناة ألفا من المصدر Argb32Colorgroupdocs.viewer.drawing/argb32color بعد التحويل لأن Rgb24Colorgroupdocs.viewer.drawing/rgb24color لا يدعم الشفافية."
type: docs
weight: 310
url: /ar/net/groupdocs.viewer.drawing/argb32color/op_explicit/
---

## Argb32Color Explicit operator

يقوم بتحويل صريح من [`Argb32Color`](../../argb32color) 32 بت إلى [`Rgb24Color`](../../rgb24color) 24 بت. سيتم فقدان قناة ألفا من المصدر [`Argb32Color`](../../argb32color) بعد التحويل، لأن [`Rgb24Color`](../../rgb24color) لا يدعم الشفافية.

```csharp
public static explicit operator Rgb24Color(Argb32Color argbColor)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| argbColor | Argb32Color | المصدر [`Argb32Color`](../../argb32color) للتحويل |

### انظر أيضًا

* struct [Rgb24Color](../../rgb24color)
* struct [Argb32Color](../../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
