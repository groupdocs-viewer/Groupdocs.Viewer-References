---
title: "GetResourceFilter"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कैश एंट्रीज़ को खोजने के लिए फ़िल्टर स्ट्रिंग लौटाता है जो Resourcegroupdocs.viewer.results/resource ऑब्जेक्ट्स का प्रतिनिधित्व करती है।"
type: docs
weight: 60
url: /hi/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

कैश एंट्रीज़ को खोजने के लिए फ़िल्टर स्ट्रिंग लौटाता है जो [`Resource`](../../../groupdocs.viewer.results/resource) ऑब्जेक्ट्स का प्रतिनिधित्व करती है।

```csharp
public static string GetResourceFilter(int pageNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |

### वापसी मान

कैश एंट्रीज़ को खोजने के लिए फ़िल्टर स्ट्रिंग जो [`Resource`](../../../groupdocs.viewer.results/resource) ऑब्जेक्ट्स का प्रतिनिधित्व करती है।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *pageNumber* शून्य या उससे कम हो तो फेंका जाता है। |

### संबंधित देखें

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
