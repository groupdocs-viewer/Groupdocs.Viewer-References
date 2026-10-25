---
title: "SearchHighlightOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يوفر خيارات للبحث وتحديد النص في المستندات التي تم تحميلها إلى عارض../groupdocs.viewer/viewer class"
type: docs
weight: 500
url: /ar/net/groupdocs.viewer.options/searchhighlightoptions/
---

## SearchHighlightOptions class

يوفر خيارات للبحث وتحديد النص في المستندات، التي تم تحميلها إلى الفئة [`Viewer`](../../groupdocs.viewer/viewer)

```csharp
public sealed class SearchHighlightOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SearchHighlightOptions](searchhighlightoptions)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/searchhighlightoptions/backgroundcolor) { get; set; } | يحصل أو يعيّن لون الخلفية للتحديد |
| [ForegroundColor](../../groupdocs.viewer.options/searchhighlightoptions/foregroundcolor) { get; set; } | يحصل أو يعيّن لون المقدمة (النص) للتحديد |
| [IsSearchTermRegEx](../../groupdocs.viewer.options/searchhighlightoptions/issearchtermregex) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب معالجة مصطلح البحث كتعبير نمطي أو كنص حرفي. القيمة الافتراضية هي `false` — يُعامل كنص حرفي. |
| [SearchTerm](../../groupdocs.viewer.options/searchhighlightoptions/searchterm) { get; set; } | يحصل أو يعيّن النص (أو نمط التعبير النمطي، إذا كانت الخاصية [`IsSearchTermRegEx`](./issearchtermregex) `true`) للبحث عنه. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
