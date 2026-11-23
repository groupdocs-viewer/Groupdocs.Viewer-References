---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "FolderFontSourcegroupdocs.viewer.fonts/folderfontsource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

नया उदाहरण प्रारंभ करता है [`FolderFontSource`](../../folderfontsource) वर्ग का।

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| folderPath | String | फ़ोल्डर का पथ जो TrueType फ़ॉन्ट्स रखता है। |
| searchOption | SearchOption | निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए, या वर्तमान फ़ोल्डर और सभी उप-फ़ोल्डर। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *folderPath* शून्य होने पर फेंका जाता है। |
| DirectoryNotFoundException | *folderPath* में निर्दिष्ट पथ को नहीं पाया जा सकता, तो फेंका जाता है। |

### संबंधित देखें

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
