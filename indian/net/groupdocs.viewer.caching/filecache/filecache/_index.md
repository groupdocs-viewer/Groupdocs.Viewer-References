---
title: "फ़ाइलकैश"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "FileCachegroupdocs.viewer.caching/filecache क्लास का नया इंस्टेंस बनाता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.caching/filecache/filecache/
---

## FileCache(string) {#constructor}

[`FileCache`](../../filecache) क्लास का नया इंस्टेंस बनाता है।

```csharp
public FileCache(string cachePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cachePath | String | सापेक्ष या पूर्ण पथ जहाँ दस्तावेज़ कैश संग्रहीत किया जाएगा। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *cachePath* नल होने पर थ्रो किया जाता है। |

### संबंधित देखें

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

[`FileCache`](../../filecache) क्लास का नया इंस्टेंस बनाता है।

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cachePath | String | सापेक्ष या पूर्ण पथ जहाँ दस्तावेज़ कैश संग्रहीत किया जाएगा। |
| cacheSubFolder | String | *cachePath* में जोड़ने के लिए उप-फ़ोल्डर। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *cachePath* नल होने पर थ्रो किया जाता है। |
| ArgumentNullException | *cacheSubFolder* नल होने पर थ्रो किया जाता है। |

### संबंधित देखें

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
