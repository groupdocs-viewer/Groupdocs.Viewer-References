---
title: "Search"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يقوم بإجراء بحث نصي وتظليله إذا تم العثور عليه في المستند المحمَّل وفقًا للخيارات المحملة"
type: docs
weight: 80
url: /ar/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

ينفّذ بحثًا نصيًا وتظليله (إن وجد) في المستند المحمل وفقًا للخيارات المحملة.

```csharp
public void Search(SearchHighlightOptions options)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | SearchHighlightOptions | خيارات البحث والتظليل، وهذا يشمل عبارة نصية للبحث. لا يمكن أن تكون `null`. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون معامل *options* هو `null` |

### انظر أيضًا

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
