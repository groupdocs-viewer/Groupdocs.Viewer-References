---
title: "ProjectManagementViewInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "تهيئة نسخة جديدة من الفئة ProjectManagementViewInfogroupdocs.viewer.results/projectmanagementviewinfo."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/projectmanagementviewinfo/projectmanagementviewinfo/
---

## ProjectManagementViewInfo() {#constructor}

تهيئة نسخة جديدة من الفئة [`ProjectManagementViewInfo`](../../projectmanagementviewinfo).

```csharp
public ProjectManagementViewInfo()
```

### انظر أيضًا

* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ProjectManagementViewInfo(FileType, List&lt;Page&gt;, DateTime, DateTime) {#constructor_1}

تهيئة نسخة جديدة من الفئة [`ProjectManagementViewInfo`](../../projectmanagementviewinfo).

```csharp
public ProjectManagementViewInfo(FileType fileType, List<Page> pages, DateTime startDate, 
    DateTime endDate)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| fileType | FileType | نوع الملف. |
| الصفحات | List`1 | قائمة الصفحات للعرض. |
| startDate | DateTime | التاريخ والوقت الذي بدأ فيه المشروع. |
| endDate | DateTime | التاريخ والوقت الذي يجب إكمال المشروع فيه. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *fileType* فارغًا. |
| ArgumentNullException | يتم رمي الاستثناء عندما تكون *pages* فارغة. |

### انظر أيضًا

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
