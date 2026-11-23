---
title: "GetFileKey"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो फ़ाइल का प्रतिनिधित्व करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो फ़ाइल का प्रतिनिधित्व करता है।

```csharp
public static string GetFileKey(string extension)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| एक्सटेंशन | String | फ़ाइलनाम प्रत्यय (जिसमें अवधि "." शामिल है) जैसे ".doc"। |

### वापसी मान

फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री का अद्वितीय पहचानकर्ता।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *extension* शून्य या खाली हो तो फेंका जाता है। |

### संबंधित देखें

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
