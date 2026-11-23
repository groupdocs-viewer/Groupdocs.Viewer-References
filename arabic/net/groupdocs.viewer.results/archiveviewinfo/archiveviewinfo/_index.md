---
title: "ArchiveViewInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ نسخة جديدة من فئة ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---

## ArchiveViewInfo() {#constructor}

يُنشئ نسخة جديدة من فئة [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo()
```

### انظر أيضًا

* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ArchiveViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

يُنشئ نسخة جديدة من فئة [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| fileType | FileType | نوع الملف. |
| الصفحات | List`1 | قائمة الصفحات للعرض. |
| المجلدات | List`1 | قائمة المجلدات الموجودة في ملف الأرشيف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *fileType* فارغًا. |
| ArgumentNullException | يتم رمي الاستثناء عندما تكون *pages* فارغة. |
| ArgumentNullException | يتم إلقاؤه عندما يكون *folders* فارغًا. |

### انظر أيضًا

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
