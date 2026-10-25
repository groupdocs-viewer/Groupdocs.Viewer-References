---
title: "ForRenderingByScaleFactor"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلاً من الفئة CadOptionsgroupdocs.viewer.options/cadoptions للعرض حسب معامل المقياس."
type: docs
weight: 20
url: /ar/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

يُنشئ مثيلاً من الفئة [`CadOptions`](../../cadoptions) للعرض حسب معامل المقياس.

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| scaleFactor | Single | القيمة التي تزيد عن 1 تكبر نتيجة الإخراج؛ القيمة بين 0 و 1 تقلل نتيجة الإخراج. |

### قيمة الإرجاع

مثيل جديد من الفئة [`CadOptions`](../../cadoptions) للعرض حسب معامل المقياس.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *scaleFactor* أقل من أو يساوي الصفر. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### انظر أيضًا

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
