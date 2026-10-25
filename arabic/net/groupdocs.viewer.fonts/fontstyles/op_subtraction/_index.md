---
title: "op_Subtraction"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يطرح نمط الخط المحدد كالمطرح الثاني من نمط الخط المحدد كالمطرح الأول وينتج نمط خط جديد يحتوي فقط على العلامات من المعامل الأول التي لا توجد في المعامل الثاني"
type: docs
weight: 170
url: /ar/net/groupdocs.viewer.fonts/fontstyles/op_subtraction/
---

## FontStyles Subtraction operator

يطرح نمط الخط المحدد الثاني (subtrahend) من نمط الخط المحدد الأول (minuend) وينتج نمط خط جديد ناتج، حيث تكون موجودة فقط العلامات من العامل الأول التي لا توجد في العامل الثاني (difference)

```csharp
public static FontStyles operator -(FontStyles minuend, FontStyles subtrahend)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| المطرح الأول | FontStyles | معامل نمط الخط للمطرح الأول |
| المطرح الثاني | FontStyles | معامل نمط الخط للمطرح الثاني |

### قيمة الإرجاع

نتيجة الفرق بين المعامل الأول (المطرح الأول) والمعامل الثاني (المطرح الثاني)

### انظر أيضًا

* struct [FontStyles](../../fontstyles)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
