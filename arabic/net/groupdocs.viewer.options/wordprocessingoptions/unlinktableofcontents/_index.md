---
title: "UnlinkTableOfContents"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "عند التصيير إلى HTML أو PDF يمكنك تعيين هذا الخيار إلى true لتعطيل التنقل من جدول المحتويات. في تصيير HTML سيتم استبدال وسوم a ذات الروابط النسبية بوسوم span، مما يزيل الوظيفة لكنه يحافظ على المظهر البصري. في تصيير PDF سيُصَغَر جدول المحتويات كنص عادي دون روابط إلى أقسام المستند."
type: docs
weight: 110
url: /ar/net/groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents/
---

## WordProcessingOptions.UnlinkTableOfContents property

عند العرض إلى HTML أو PDF، يمكنك ضبط هذا الخيار إلى `true` لتعطيل التنقل من جدول المحتويات. بالنسبة للعرض HTML، سيتم استبدال وسوم `a` ذات الروابط النسبية بوسوم `span`، مما يزيل الوظيفة لكنه يحافظ على المظهر البصري. بالنسبة للعرض PDF، سيُعرض جدول المحتويات كنص عادي دون روابط إلى أقسام المستند.

```csharp
public bool UnlinkTableOfContents { get; set; }
```

### ملاحظات

القيمة الافتراضية هي `false`

للتفاصيل، راجع [الوثائق](https://docs.groupdocs.com/viewer/net/render-word-documents/#unlink-table-of-contents).

### انظر أيضًا

* class [WordProcessingOptions](../../wordprocessingoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
