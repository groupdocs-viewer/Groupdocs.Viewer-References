---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Word दस्तावेज़ों को रेंडर करने के विकल्प शामिल करता है। विवरण के लिए दस्तावेज़ देखें https//docs.groupdocs.com/viewer/net/renderworddocuments/।"
type: docs
weight: 630
url: /hi/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Word दस्तावेज़ों को रेंडर करने के विकल्पों को शामिल करता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](https://docs.groupdocs.com/viewer/net/render-word-documents/)।

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्प शामिल करता है। विवरण के लिए, देखें [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## गुण

| नाम | विवरण |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | पृष्ठ के नीचे मार्जिन को सेट करता है। |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | यह विकल्प अरबी, हिब्रू, भारतीय लैटिन-आधारित, या सायरिलिक-आधारित लिपियों को रेंडर करते समय कर्निंग और अन्य OpenType सुविधाएँ सक्षम करता है। |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। यह विकल्प केवल WordProcessing दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है। |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | पृष्ठ का बायाँ मार्जिन सेट करता है। |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | लोड किए गए WordProcessing दस्तावेज़ के लिए पृष्ठ क्रमांकन को बलपूर्वक लागू करने की अनुमति देता है। डिफ़ॉल्ट रूप से NotApply है — दस्तावेज़ अपरिवर्तित रहता है। |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | आउटपुट पृष्ठ का आकार। डिफ़ॉल्ट मान Unspecified है, जिसका अर्थ है कि पृष्ठ सेटिंग्स (Page Setup) में निर्धारित पृष्ठ आकार उपयोग किया जाता है। HTM और HTML फ़ाइलों को रेंडर करते समय डिफ़ॉल्ट पृष्ठ आकार Letter 792 x 612 पॉइंट्स पर सेट होता है। परिणामस्वरूप, कुछ सामग्री पृष्ठ फ्रेम में फिट नहीं हो सकती। सामग्री को फिट करने के लिए बड़ा पृष्ठ आकार, जैसे A3, सेट करें। |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | ट्रैक्ड परिवर्तन (रिवीजन) रेंडरिंग को सक्षम करता है। |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | पृष्ठ का दायाँ मार्जिन सेट करता है। |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | पृष्ठ का शीर्ष मार्जिन सेट करता है। |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | HTML या PDF में रेंडर करते समय, आप इस विकल्प को `true` सेट करके सामग्री तालिका से नेविगेशन को निष्क्रिय कर सकते हैं। HTML रेंडरिंग के लिए, सापेक्ष लिंक वाले `a` टैग को `span` टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाएगी लेकिन दृश्य रूप बना रहेगा। PDF रेंडरिंग के लिए, सामग्री तालिका को साधारण टेक्स्ट के रूप में रेंडर किया जाएगा बिना दस्तावेज़ अनुभागों के लिंक के। |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | निर्धारित करता है कि कुछ प्रकार के फ़ील्ड को इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले अपडेट किया जाना चाहिए या नहीं। इस प्रॉपर्टी का डिफ़ॉल्ट मान `true` है — फ़ील्ड सहेजने से पहले अपडेट हो जाएंगे। |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में लंबवत रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। यह विकल्प केवल WordProcessing दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | इस विकल्प की पूरी गहरी कॉपी बनाता है और लौटाता है। |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | निर्धारित करता है कि निर्दिष्ट [`WordProcessingOptions`](../wordprocessingoptions) का उदाहरण इस के बराबर है या नहीं। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
