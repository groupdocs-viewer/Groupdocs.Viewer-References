---
title: "DisableCopyProtection"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعطل حماية نسخ المحتوى عند تصيير إلى HTML."
type: docs
weight: 30
url: /ar/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

يعطل حماية نسخ المحتوى عند تصيير إلى HTML.

```csharp
public bool DisableCopyProtection { get; set; }
```

### ملاحظات

عند عرض ملفات PDF مع حماية ضد نسخ النصوص والصور إلى HTML، يضيف GroupDocs.Viewer سمة HTML 'inert' إلى وسم HTML BODY. القيمة الافتراضية لهذا الخيار هي `false`، مما يشير إلى أن سمة HTML 'intent' تُضاف فقط إذا كان مستند PDF محميًا.

للحصول على مثال على الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### انظر أيضًا

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
