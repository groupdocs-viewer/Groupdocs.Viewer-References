---
title: "للتصوير حسب العرض والارتفاع"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ مثيلاً لفئة CadOptionsgroupdocs.viewer.options/cadoptions للتصوير حسب العرض والارتفاع."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

ينشئ مثيلاً لفئة [`CadOptions`](../../cadoptions) للتصوير حسب العرض والارتفاع.

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض نتيجة الإخراج (بالبكسل). |
| الارتفاع | Int32 | ارتفاع النتيجة الناتجة (بالبكسل). |

### قيمة الإرجاع

مثيل جديد لفئة [`CadOptions`](../../cadoptions) للتصوير حسب العرض والارتفاع.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *العرض* أقل من أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *الارتفاع* أقل من أو يساوي الصفر. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### انظر أيضًا

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
