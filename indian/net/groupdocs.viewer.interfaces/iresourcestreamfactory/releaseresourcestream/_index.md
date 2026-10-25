---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream मेथड द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

[`CreateResourceStream`](../createresourcestream) मेथड द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है।

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | एक पृष्ठ की संख्या। |
| संसाधन | संसाधन | फ़ॉन्ट, शैली, छवि या ग्राफ़िक्स जैसी HTML संसाधन। |
| resourceStream | Stream | [`CreateResourceStream`](../createresourcestream) मेथड द्वारा बनाई गई स्ट्रीम। |

### संबंधित देखें

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
