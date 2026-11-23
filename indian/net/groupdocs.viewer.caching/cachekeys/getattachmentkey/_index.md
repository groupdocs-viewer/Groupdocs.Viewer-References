---
title: "GetAttachmentKey"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो संलग्न फ़ाइल का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो संलग्न फ़ाइल का प्रतिनिधित्व करता है।

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attachmentId | String | एकल फ़ाइल के संदर्भ में अनुलग्नक का अद्वितीय पहचानकर्ता। |

### वापसी मान

कैश एंट्री के लिए अद्वितीय पहचानकर्ता जो अनुलग्नक फ़ाइल का प्रतिनिधित्व करता है।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *attachmentId* null या खाली हो तो फेंका जाता है। |

### संबंधित देखें

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
