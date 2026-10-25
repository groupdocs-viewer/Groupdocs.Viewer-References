---
title: "MaxItemsInFolder"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer.options/outlookoptions/maxitemsinfolder/
---

## OutlookOptions.MaxItemsInFolder property

الحد الأقصى لعدد الرسائل أو العناصر التي يمكن تصييرها من مجلد واحد.

```csharp
public int MaxItemsInFolder { get; set; }
```

### ملاحظات

يمكن أن تكون ملفات بيانات Outlook كبيرة وقد يستغرق استرجاع جميع الرسائل وقتًا كبيرًا. هذه الخاصية تحدّ من الحد الأقصى لعدد الرسائل أو العناصر التي يتم عرضها. القيمة الافتراضية هي `50`. لعرض جميع الرسائل، اضبط القيمة إلى `0`.

للحصول على مثال شفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).

### انظر أيضًا

* class [OutlookOptions](../../outlookoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
