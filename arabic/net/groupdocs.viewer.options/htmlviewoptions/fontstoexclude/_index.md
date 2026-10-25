---
title: "FontsToExclude"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "قائمة أسماء الخطوط التي يجب استبعادها من مستند HTML."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---

## HtmlViewOptions.FontsToExclude property

قائمة أسماء الخطوط التي يجب استبعادها من مستند HTML.

```csharp
public List<string> FontsToExclude { get; set; }
```

### ملاحظات

الخطوط التي تُضاف إلى مستند HTML تحسّن استقرار العرض الناتج، وفي الوقت نفسه تزيد من حجم نتيجة التجسيد. يتيح لك هذا الخيار الموازنة بين الاستقرار وحجم الإخراج. قم بتضمين أسماء الخطوط الشائعة والمثبتة في معظم الأنظمة.

يرجى ملاحظة أن هذه الخاصية نشطة فقط عندما يكون خيار [`ExcludeFonts`](../excludefonts) معطَّل.

للتفاصيل ومثال الكود، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/exclude-fonts/).

### انظر أيضًا

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
