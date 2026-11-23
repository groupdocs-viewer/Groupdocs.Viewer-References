---
title: "ForSplitSheetIntoPages"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُهيئ مثيلًا من الفئة SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions لتصوير الورقة إلى صفحات."
type: docs
weight: 50
url: /ar/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

يُهيئ مثيلًا من الفئة [`SpreadsheetOptions`](../../spreadsheetoptions) لتصوير الورقة إلى صفحات.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| countRowsPerPage | Int32 | عدد الصفوف التي تُدرج في كل صفحة. |

### قيمة الإرجاع

مثال جديد من الفئة [`SpreadsheetOptions`](../../spreadsheetoptions) لتصوير الورقة إلى صفحات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *countRowsPerPage* مساويًا أو أقل من الصفر. |

### ملاحظات

للتفاصيل، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### انظر أيضًا

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

يُهيئ مثيلًا من الفئة [`SpreadsheetOptions`](../../spreadsheetoptions) لتصوير الورقة إلى صفحات.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| countRowsPerPage | Int32 | عدد الصفوف التي تُدرج في كل صفحة. |
| countColumnsPerPage | Int32 | عدد الأعمدة التي تُدرج في كل صفحة. |

### قيمة الإرجاع

مثال جديد من الفئة [`SpreadsheetOptions`](../../spreadsheetoptions) لتصوير الورقة إلى صفحات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *countRowsPerPage* مساويًا أو أقل من الصفر. |
| ArgumentException | يُرمى عندما يكون *countColumnsPerPage* مساويًا أو أقل من الصفر. |

### ملاحظات

للتفاصيل، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### انظر أيضًا

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
