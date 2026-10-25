---
title: "TryRepair"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي false."
type: docs
weight: 80
url: /ar/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي `false`.

```csharp
public bool TryRepair { get; set; }
```

### ملاحظات

تتعامل هذه الميزة مع المشكلات التالية في مستند PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### انظر أيضًا

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
