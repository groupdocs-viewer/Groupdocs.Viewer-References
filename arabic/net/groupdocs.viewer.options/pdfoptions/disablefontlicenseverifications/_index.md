---
title: "DisableFontLicenseVerifications"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

يعطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### ملاحظات

العديد من العمليات مع الخط لا يمكن تنفيذها إذا كانت محظورة بموجب ترخيص هذا الخط. على سبيل المثال، لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. يتيح لك هذا الخيار تخطي التحقق من هذه القواعد.

احرص على الحذر عند استخدام هذه العلامة. عندما يتم تعيينها، فهذا يعني أن الشخص الذي يضع هذه العلامة يتحمل جميع المسؤولية عن أي انتهاكات محتملة للترخيص/القانون بنفسه. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر. القيمة الافتراضية هي `false`.

للحصول على مثال على الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### انظر أيضًا

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
