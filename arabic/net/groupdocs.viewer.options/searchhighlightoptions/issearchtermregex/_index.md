---
title: "IsSearchTermRegEx"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب معالجة مصطلح البحث كتعبير نمطي أو كنص حرفي. القيمة الافتراضية هي false وتعامل كنص حرفي."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب معالجة مصطلح البحث كتعبير نمطي أو كنص حرفي. القيمة الافتراضية هي `false` — يُعامل كنص حرفي.

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### ملاحظات

إذا كانت `true`، يتم تفسير [`SearchTerm`](../searchterm) كنمط Regex في .NET.

إذا كانت `false`، يتم البحث عن [`SearchTerm`](../searchterm) كنص حرفي في المستند.

### انظر أيضًا

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
