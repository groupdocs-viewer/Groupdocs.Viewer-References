---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF ऑप्टिमाइज़ेशन विकल्प शामिल हैं। विवरण और कोड नमूने के लिए देखें यह पृष्ठ https//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ और इसके चाइल्ड।"
type: docs
weight: 400
url: /hi/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF ऑप्टिमाइज़ेशन विकल्प शामिल हैं। विवरण और कोड उदाहरणों के लिए, देखें यह [पृष्ठ](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) और इसके चाइल्ड।

```csharp
public class PdfOptimizationOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | MaxResolution विकल्प का डिफ़ॉल्ट मान 300 और ImageQuality विकल्प का डिफ़ॉल्ट मान 100 सेट करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | आउटपुट PDF फ़ाइल में छवियों को संपीड़ित करने को सक्षम करता है। |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | आउटपुट PDF फ़ाइल को ग्रेस्केल में बदलने को सक्षम करता है। |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | आउटपुट PDF फ़ाइल में छवि गुणवत्ता (प्रतिशत में) सेट करता है। |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | वेब ब्राउज़र के साथ ऑनलाइन देखने के लिए आउटपुट PDF फ़ाइल का ऑप्टिमाइज़ेशन सक्षम करता है। |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | आउटपुट PDF फ़ाइल में अधिकतम रिज़ॉल्यूशन सेट करता है। |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | PDF फ़ाइलों में स्प्रेडशीट्स के ऑप्टिमाइज़ेशन को सक्षम करता है। |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | आउटपुट PDF फ़ाइल से एनोटेशन हटाने को सक्षम करता है। |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | PDF फ़ाइल से फ़ॉर्म फ़ील्ड हटाने को सक्षम करता है। |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | PDF फ़ाइल से अनउपयोगी (अनाथ) ऑब्जेक्ट हटाता है, जो PDF दस्तावेज़ में रखे गए हैं, लेकिन किसी पृष्ठ के रिसोर्स डिक्शनरी से संदर्भित नहीं होते और इसलिए बिल्कुल भी उपयोग नहीं होते। इस प्रॉपर्टी को सक्रिय करने से (`true`) आउटपुट PDF दस्तावेज़ का आकार घटेगा। डिफ़ॉल्ट रूप से यह अक्षम है (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | PDF फ़ाइल से अनउपयोगी (अनाथ) स्ट्रीम हटाता है, जो पृष्ठ के रिसोर्स डिक्शनरी से अभी भी संदर्भित हैं, लेकिन वास्तव में पृष्ठ सामग्री में कभी उपयोग नहीं होते। डिफ़ॉल्ट रूप से यह अक्षम है (`false`), इसे सक्षम करने से (`true`) आउटपुट PDF दस्तावेज़ का आकार घटेगा। |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | आउटपुट PDF फ़ाइल में अधिकतम रिज़ॉल्यूशन सेट करने को सक्षम करता है। |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | आउटपुट PDF फ़ाइल में फ़ॉन्ट के उपसमुच्चय बनाता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
