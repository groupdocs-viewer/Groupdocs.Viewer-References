---
title: "RotatePage"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يطبق الدوران في اتجاه عقارب الساعة على الصفحة."
type: docs
weight: 30
url: /ar/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

يطبق الدوران في اتجاه عقارب الساعة على الصفحة.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة، يجب أن يكون أكبر من 0 بشكل صارم. |
| rotation | Rotation | قيمة الدوران. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يتم إلقاؤه عندما تكون *pageNumber* أقل أو مساوية للصفر. |
| ArgumentException | يتم إلقاؤه عندما يكون الدوران للصفحة ذات الرقم *pageNumber* قد أُضيف بالفعل. |

### ملاحظات

للتفاصيل، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/).

### انظر أيضًا

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
