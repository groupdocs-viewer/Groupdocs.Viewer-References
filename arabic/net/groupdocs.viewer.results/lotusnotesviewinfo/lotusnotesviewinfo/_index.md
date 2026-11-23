---
title: "LotusNotesViewInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلًا جديدًا من الفئة LotusNotesViewInfogroupdocs.viewer.results/lotusnotesviewinfo."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/lotusnotesviewinfo/lotusnotesviewinfo/
---

## LotusNotesViewInfo() {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`LotusNotesViewInfo`](../../lotusnotesviewinfo).

```csharp
public LotusNotesViewInfo()
```

### انظر أيضًا

* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## LotusNotesViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

يُنشئ مثيلًا جديدًا من الفئة [`LotusNotesViewInfo`](../../lotusnotesviewinfo).

```csharp
public LotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| fileType | FileType | نوع الملف. |
| الصفحات | List`1 | قائمة الصفحات للعرض. |
| notesCount | Int32 | عدد الملاحظات الموجود في ملف تخزين قاعدة بيانات Lotus. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *fileType* فارغًا. |
| ArgumentNullException | يتم رمي الاستثناء عندما تكون *pages* فارغة. |
| ArgumentNullException | يُرمى عندما تكون *notesCount* null. |

### انظر أيضًا

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
