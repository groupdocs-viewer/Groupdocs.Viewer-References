---
title: "RenderNotes"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कुछ फ़ॉर्मैट्स के लिए नोट्स और एनोटेशन की रेंडरिंग को सक्षम करता है।"
type: docs
weight: 120
url: /hi/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

कुछ फ़ॉर्मैट्स के लिए नोट्स और एनोटेशन की रेंडरिंग को सक्षम करता है।

```csharp
public bool RenderNotes { get; set; }
```

### टिप्पणियाँ

कुछ फ़ॉर्मेट, जैसे प्रस्तुतियाँ या Microsoft प्रोजेक्ट फ़ाइलें, में नोट्स हो सकते हैं। साथ ही, PDF फ़ाइलों में पॉप‑अप एनोटेशन (baloon hints) हो सकते हैं, जो डिफ़ॉल्ट रूप से छिपे होते हैं और केवल PDF व्यूअर में माउस कर्सर को उन पर ले जाने पर दिखते हैं। डिफ़ॉल्ट रूप से, GroupDocs.Viewer ऐसे नोट्स और एनोटेशन (`false`) को रेंडर नहीं करता। इसे करने के लिए, इस प्रॉपर्टी को `true` सेट करें।

कोड उदाहरण के लिए, देखें [documentation](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes).

### संबंधित देखें

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
