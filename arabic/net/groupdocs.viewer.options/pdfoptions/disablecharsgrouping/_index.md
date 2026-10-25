---
title: "DisableCharsGrouping"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعطل تجميع الرموز لتحديد موضع الرموز بدقة أثناء تصيير الصفحة."
type: docs
weight: 20
url: /ar/net/groupdocs.viewer.options/pdfoptions/disablecharsgrouping/
---

## PdfOptions.DisableCharsGrouping property

يعطل تجميع الرموز لتحديد موضع الرموز بدقة أثناء تصيير الصفحة.

```csharp
public bool DisableCharsGrouping { get; set; }
```

### ملاحظات

عند تحويل ملفات PDF، يقوم GroupDocs.Viewer بتجميع الأحرف الفردية إلى كلمات لتحسين أداء العرض. إذا كان مستندك يحتوي على رموز هيروغليفية أو رموز خاصة، قد ترغب في منع تجميع الأحرف لضمان تخطيط أكثر دقة. القيمة الافتراضية هي `false`.

للحصول على مثال على الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-character-grouping).

### انظر أيضًا

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
