---
title: "FolderFontSource"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثالًا جديدًا من الفئة FolderFontSourcegroupdocs.viewer.fonts/folderfontsource."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

يُنشئ مثيلاً جديدًا من الفئة [`FolderFontSource`](../../folderfontsource).

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| folderPath | String | المسار إلى المجلد الذي يحتوي على خطوط TrueType. |
| searchOption | SearchOption | يحدد ما إذا كان يجب البحث في المجلد الحالي، أو في المجلد الحالي وجميع المجلدات الفرعية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *folderPath* فارغًا. |
| DirectoryNotFoundException | يُرمى عندما لا يمكن العثور على المسار المحدد في *folderPath*. |

### انظر أيضًا

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
