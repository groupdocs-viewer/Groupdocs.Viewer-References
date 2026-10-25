---
title: "GetPageKey"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो पृष्ठ फ़ाइल का प्रतिनिधित्व करता है।"
type: docs
weight: 50
url: /hi/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो पृष्ठ फ़ाइल का प्रतिनिधित्व करता है।

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |
| एक्सटेंशन | String | फ़ाइलनाम प्रत्यय (जिसमें अवधि "." शामिल है) जैसे ".doc"। |

### वापसी मान

कैश एंट्री के लिए अद्वितीय पहचानकर्ता जो पृष्ठ फ़ाइल का प्रतिनिधित्व करता है।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *pageNumber* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब *extension* शून्य या खाली हो तो फेंका जाता है। |

### संबंधित देखें

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
