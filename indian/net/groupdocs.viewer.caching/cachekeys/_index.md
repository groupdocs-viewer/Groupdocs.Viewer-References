---
title: "कैश कुंजियाँ"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करने के तरीकों को प्रदान करता है।"
type: docs
weight: 980
url: /hi/net/groupdocs.viewer.caching/cachekeys/
---

## CacheKeys class

कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करने के तरीकों को प्रदान करता है।

```csharp
public static class CacheKeys
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [GetAttachmentKey](../../groupdocs.viewer.caching/cachekeys/getattachmentkey)(string) | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो संलग्न फ़ाइल का प्रतिनिधित्व करता है। |
| static [GetAttachmentsKey](../../groupdocs.viewer.caching/cachekeys/getattachmentskey)() | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो [`Attachment`](../../groupdocs.viewer.results/attachment) वस्तुओं के संग्रह का प्रतिनिधित्व करता है। |
| static [GetFileInfoKey](../../groupdocs.viewer.caching/cachekeys/getfileinfokey)() | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो [`ViewInfo`](../../groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| static [GetFileKey](../../groupdocs.viewer.caching/cachekeys/getfilekey)(string) | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो फ़ाइल का प्रतिनिधित्व करता है। |
| static [GetPageKey](../../groupdocs.viewer.caching/cachekeys/getpagekey)(int, string) | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो पृष्ठ फ़ाइल का प्रतिनिधित्व करता है। |
| static [GetResourceFilter](../../groupdocs.viewer.caching/cachekeys/getresourcefilter)(int) | कैश प्रविष्टियों को खोजने के लिए फ़िल्टर स्ट्रिंग लौटाता है जो [`Resource`](../../groupdocs.viewer.results/resource) वस्तुओं का प्रतिनिधित्व करती हैं। |
| static [GetResourceKey](../../groupdocs.viewer.caching/cachekeys/getresourcekey)(int, Resource) | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो [`Resource`](../../groupdocs.viewer.results/resource) ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| static [GetViewInfoKey](../../groupdocs.viewer.caching/cachekeys/getviewinfokey)() | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता लौटाता है जो [`ViewInfo`](../../groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
