---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "प्रेजेंटेशन को रेंडर करने के विकल्प शामिल करता है। विवरण के लिए दस्तावेज़ देखें https//docs.groupdocs.com/viewer/net/renderpresentations/।"
type: docs
weight: 460
url: /hi/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

प्रेज़ेंटेशन को रेंडर करने के विकल्प शामिल हैं। विवरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/render-presentations/)।

```csharp
public class PresentationOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [PresentationOptions](presentationoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | स्लाइड के हेडर और फ़ूटर में प्लेसहोल्डर रेंडरिंग को सक्षम करता है। डिफ़ॉल्ट रूप से अक्षम (`false`) है। यह विकल्प प्रेजेंटेशन के सभी 4 रेंडरिंग मोड्स पर लागू होता है: HTML, PDF, PNG, और JPEG। जब प्रेजेंटेशन को शुद्ध HTML/CSS मार्कअप में रेंडर किया जाता है, तो [`RenderToPureHtml`](./rendertopurehtml) का उपयोग करके यह लागू नहीं होता। |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | प्रेजेंटेशन दस्तावेज़ों के लिए एक नया HTML रेंडरिंग मोड सक्षम करता है — इस मोड में प्रेजेंटेशन फ़ाइलें **pure HTML/CSS markup** में रेंडर की जाती हैं, बिना SVG छवियों के। डिफ़ॉल्ट रूप से यह अक्षम (`false`) है — मौजूदा SVG-आधारित HTML-रेंडरर उपयोग किया जाता है। |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | प्रेजेंटेशन छवियों का रिज़ॉल्यूशन (केवल HTML/PDF में रेंडर करने के लिए)। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
