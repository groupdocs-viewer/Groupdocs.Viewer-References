---
title: "LoadOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प शामिल करता है। विवरण के लिए इस पृष्ठ https//docs.groupdocs.com/viewer/net/loading/ और इसके उप‑पृष्ठ देखें।"
type: docs
weight: 360
url: /hi/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प शामिल हैं। विवरण के लिए, देखें यह [पृष्ठ](https://docs.groupdocs.com/viewer/net/loading/) और इसके चाइल्ड।

```csharp
public class LoadOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | [`LoadOptions`](../loadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| [LoadOptions](loadoptions#constructor_1)(FileType) | [`LoadOptions`](../loadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) और [`TSV`](../../groupdocs.viewer/filetype/tsv) फ़ाइलों के लिए एन्कोडिंग डिटेक्शन को सक्षम करता है। |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | टेक्स्ट‑आधारित फ़ाइलें या ई‑मेल संदेश जैसे [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) और [`MSG`](../../groupdocs.viewer/filetype/msg) खोलते समय उपयोग की जाने वाली एन्कोडिंग सेट करता है। डिफ़ॉल्ट मान UTF8 है। |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | खोलने वाली फ़ाइल का प्रकार सेट करता है। |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड सेट करता है। |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | बाहरी संसाधनों को लोड करने के लिए टाइमआउट सेट करता है। |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | छवियों जैसे सभी बाहरी संसाधनों के लोडिंग को निष्क्रिय करता है, सिवाय [`WhitelistedResources`](./whitelistedresources) के। |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | सक्षम होने पर GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान `false` है। |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | जब [`SkipExternalResources`](./skipexternalresources) को `true` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL फ्रैगमेंट की सूची। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
