---
title: "फ़ाइलकैश"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "स्थानीय ऑन-डिस्क कैश का प्रतिनिधित्व करता है।"
type: docs
weight: 990
url: /hi/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

स्थानीय ऑन-डिस्क कैश का प्रतिनिधित्व करता है।

```csharp
public class FileCache : ICache
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [FileCache](filecache#constructor)(string) | नया उदाहरण बनाता है [`FileCache`](../filecache) क्लास का। |
| [FileCache](filecache#constructor_1)(string, string) | नया उदाहरण बनाता है [`FileCache`](../filecache) क्लास का। |

## गुण

| नाम | विवरण |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | कैश फ़ोल्डर का सापेक्ष या पूर्ण पथ। |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | [`CachePath`](./cachepath) में जोड़ने के लिए उप-फ़ोल्डर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | फ़ाइलनाम में फ़िल्टर शामिल करने वाली सभी फ़ाइल नाम लौटाता है। |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | डेटा को स्थानीय डिस्क पर क्रमबद्ध करता है। |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | यदि मौजूद हो तो इस कुंजी से जुड़े डेटा को क्रमविहीन करता है। |

### संबंधित देखें

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
