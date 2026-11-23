---
title: "TryGetValue"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "यदि मौजूद हो तो इस कुंजी से संबंधित प्रविष्टि प्राप्त करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

यदि मौजूद हो तो इस कुंजी से संबंधित प्रविष्टि प्राप्त करता है।

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| पैरामीटर | विवरण |
| --- | --- |
| TEntry | एंट्री का प्रकार। |
| कुंजी | अनुरोधित एंट्री की पहचान करने वाली कुंजी। |
| मान | पाया गया मान या नल। |

### वापसी मान

```csharp
True
```

यदि कुंजी मिली थी।

### संबंधित देखें

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
