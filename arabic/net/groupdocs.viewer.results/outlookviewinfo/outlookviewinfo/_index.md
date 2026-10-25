---
title: "OutlookViewInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلًا جديدًا من الفئة OutlookViewInfogroupdocs.viewer.results/outlookviewinfo."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/outlookviewinfo/outlookviewinfo/
---

## OutlookViewInfo() {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo()
```

### انظر أيضًا

* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## OutlookViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

يُنشئ مثيلًا جديدًا من الفئة [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| fileType | FileType | نوع الملف. |
| الصفحات | List`1 | قائمة الصفحات للعرض. |
| المجلدات | List`1 | قائمة المجلدات الموجودة في ملف بيانات Outlook. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *fileType* فارغًا. |
| ArgumentNullException | يتم رمي الاستثناء عندما تكون *pages* فارغة. |
| ArgumentNullException | يتم إلقاؤه عندما يكون *folders* فارغًا. |

### انظر أيضًا

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
