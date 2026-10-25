---
title: "ICache"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "रेंडर किए गए दस्तावेज़ और दस्तावेज़ संसाधनों को संग्रहीत करने के लिए आवश्यक तरीकों को परिभाषित करता है।"
type: docs
weight: 1000
url: /hi/net/groupdocs.viewer.caching/icache/
---

## ICache interface

रेंडर किए गए दस्तावेज़ और दस्तावेज़ संसाधनों को संग्रहीत करने के लिए आवश्यक तरीकों को परिभाषित करता है।

```csharp
public interface ICache
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | फ़िल्टर से मेल खाने वाली सभी कुंजियाँ लौटाता है। |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | कैश में एक कैश प्रविष्टि सम्मिलित करता है। |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | यदि मौजूद हो तो इस कुंजी से संबंधित प्रविष्टि प्राप्त करता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
