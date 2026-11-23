---
title: "Search"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "लोड किए गए दस्तावेज़ में टेक्स्ट खोज करता है और यदि पाया जाए तो लोड किए गए विकल्पों के अनुसार उसे हाइलाइट करता है।"
type: docs
weight: 80
url: /hi/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

लोड किए गए दस्तावेज़ में लोडेड विकल्पों के अनुसार टेक्स्ट खोज करता है और यदि मिला तो उसे हाइलाइट करता है।

```csharp
public void Search(SearchHighlightOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | SearchHighlightOptions | खोज और हाइलाइट विकल्प, इसमें खोजने के लिए एक पाठ वाक्यांश शामिल है। `null` नहीं हो सकता। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* तर्क `null` हो तो यह फेंका जाता है। |

### संबंधित देखें

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
