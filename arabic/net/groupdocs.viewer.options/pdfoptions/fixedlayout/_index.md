---
title: "FixedLayout"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يفعل تصيير مستندات PDF و EPUB إلى HTML بتخطيط ثابت."
type: docs
weight: 70
url: /ar/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

يفعل تصيير مستندات PDF و EPUB إلى HTML بتخطيط ثابت.

```csharp
public bool FixedLayout { get; set; }
```

### ملاحظات

يتم في البداية عرض مستندات PDF و EPUB إلى HTML باستخدام تخطيط ثابت للحفاظ على مظهر المستند الأصلي. يعني هذا التخطيط الثابت أن جميع عناصر HTML لها مواضع دقيقة داخل حاوية ذات حجم محدد. تغيير حجم نافذة المتصفح لا يؤثر على موضع وحجم العناصر في المستند.

هذا الخيار متاح فقط عند العرض إلى HTML. القيمة الافتراضية هي `true`. لعرض باستخدام تخطيط مرن، اضبط هذه الخاصية على `false`.

عند العرض باستخدام تخطيط مرن، يتم تخطي الصور. استخدم التخطيط المرن عند عرض مستندات PDF التي تحتوي على محتوى نصي.

للحصول على مثال على الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### انظر أيضًا

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
