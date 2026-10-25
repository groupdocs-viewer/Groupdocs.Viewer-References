---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "स्ट्रीम को रिलीज़ करता है जो CreateResourceStream./createresourcestream डेलीगेट से जुड़े मेथड द्वारा निर्मित था।"
type: docs
weight: 730
url: /hi/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

स्ट्रीम को रिलीज़ करता है जो [`CreateResourceStream`](../createresourcestream) डेलीगेट से जुड़े मेथड द्वारा निर्मित था।

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |
| संसाधन | संसाधन | फ़ॉन्ट, शैली, छवि या ग्राफ़िक्स जैसे HTML संसाधन। |
| resourceStream | Stream | स्ट्रीम जो [`CreateResourceStream`](../createresourcestream) डेलीगेट से जुड़े मेथड द्वारा बनाई गई है। |

### संबंधित देखें

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
