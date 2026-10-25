---
title: "UnlinkTableOfContents"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "HTML या PDF में रेंडर करते समय आप इस विकल्प को true सेट करके टेबल ऑफ़ कंटेंट्स से नेविगेशन को निष्क्रिय कर सकते हैं। HTML रेंडरिंग में रिलेटिव लिंक वाले a टैग को span टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाती है लेकिन दृश्य रूप बना रहता है। PDF रेंडरिंग में टेबल ऑफ़ कंटेंट्स को साधारण टेक्स्ट के रूप में रेंडर किया जाएगा, जिसमें दस्तावेज़ सेक्शन के लिंक नहीं होंगे।"
type: docs
weight: 110
url: /hi/net/groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents/
---

## WordProcessingOptions.UnlinkTableOfContents property

HTML या PDF में रेंडर करते समय, आप इस विकल्प को `true` सेट करके सामग्री तालिका से नेविगेशन को निष्क्रिय कर सकते हैं। HTML रेंडरिंग के लिए, सापेक्ष लिंक वाले `a` टैग को `span` टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाएगी लेकिन दृश्य रूप बना रहेगा। PDF रेंडरिंग के लिए, सामग्री तालिका को साधारण टेक्स्ट के रूप में रेंडर किया जाएगा बिना दस्तावेज़ अनुभागों के लिंक के।

```csharp
public bool UnlinkTableOfContents { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट मान `false` है।

विवरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/render-word-documents/#unlink-table-of-contents).

### संबंधित देखें

* class [WordProcessingOptions](../../wordprocessingoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
