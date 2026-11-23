---
title: "CreateResourceUrl"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "HTML संसाधन के लिए URL बनाने वाली विधि को दर्शाता है।"
type: docs
weight: 740
url: /hi/net/groupdocs.viewer.interfaces/createresourceurl/
---

## CreateResourceUrl delegate

HTML संसाधन के लिए URL बनाने वाली विधि को दर्शाता है।

```csharp
public delegate string CreateResourceUrl(int pageNumber, Resource resource);
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |
| संसाधन | संसाधन | फ़ॉन्ट, शैली, छवि या ग्राफ़िक्स जैसे HTML संसाधन। |

### वापसी मान

HTML संसाधन का URL।

### संबंधित देखें

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
