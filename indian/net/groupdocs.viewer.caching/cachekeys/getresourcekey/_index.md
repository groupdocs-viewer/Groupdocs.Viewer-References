---
title: "GetResourceKey"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है जो Resourcegroupdocs.viewer.results/resource ऑब्जेक्ट का प्रतिनिधित्व करता है।"
type: docs
weight: 70
url: /hi/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है जो [`Resource`](../../../groupdocs.viewer.results/resource) ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |
| संसाधन | संसाधन | HTML संसाधन। |

### वापसी मान

कैश एंट्री के लिए अद्वितीय पहचानकर्ता जो [`Resource`](../../../groupdocs.viewer.results/resource) ऑब्जेक्ट का प्रतिनिधित्व करता है।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *pageNumber* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentNullException | जब *resource* null हो तो फेंका जाता है। |

### संबंधित देखें

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
