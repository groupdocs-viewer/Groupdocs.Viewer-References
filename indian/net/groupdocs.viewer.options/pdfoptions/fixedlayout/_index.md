---
title: "FixedLayout"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "PDF और EPUB दस्तावेज़ों को स्थिर लेआउट के साथ HTML में रेंडर करने को सक्षम करता है।"
type: docs
weight: 70
url: /hi/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

PDF और EPUB दस्तावेज़ों को स्थिर लेआउट के साथ HTML में रेंडर करने को सक्षम करता है।

```csharp
public bool FixedLayout { get; set; }
```

### टिप्पणियाँ

PDF और EPUB दस्तावेज़ प्रारंभिक रूप से HTML में एक स्थिर लेआउट के साथ रेंडर किए जाते हैं ताकि स्रोत दस्तावेज़ की उपस्थिति बनी रहे। यह स्थिर लेआउट का अर्थ है कि सभी HTML तत्व एक निर्धारित आकार वाले कंटेनर के भीतर सटीक स्थितियों पर होते हैं। ब्राउज़र विंडो का आकार बदलने से दस्तावेज़ में तत्वों की स्थिति और आकार प्रभावित नहीं होते।

यह विकल्प केवल HTML में रेंडर करने पर उपलब्ध है। डिफ़ॉल्ट मान `true` है। फ्लुइड लेआउट के साथ रेंडर करने के लिए, इस प्रॉपर्टी को `false` सेट करें।

फ्लुइड लेआउट में रेंडर करने पर छवियों को छोड़ दिया जाता है। टेक्स्ट सामग्री वाले PDF दस्तावेज़ों को रेंडर करते समय फ्लुइड लेआउट का उपयोग करें।

कोड उदाहरण के लिए, देखें [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### संबंधित देखें

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
