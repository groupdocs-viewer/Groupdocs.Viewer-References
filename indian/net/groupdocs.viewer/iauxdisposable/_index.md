---
title: "IAuxDisposable"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "मानक IDisposable इंटरफ़ेस को विस्तारित करता है, जिससे किसी वस्तु की वर्तमान स्थिति प्राप्त की जा सकती है और निपटान इवेंट की सदस्यता ली जा सकती है।"
type: docs
weight: 20
url: /hi/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

मानक IDisposable इंटरफ़ेस को विस्तारित करता है, जिससे किसी वस्तु की वर्तमान स्थिति प्राप्त की जा सकती है और डिस्पोज़ इवेंट की सदस्यता ली जा सकती है।

```csharp
public interface IAuxDisposable : IDisposable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | यह दर्शाता है कि कोई संसाधन पहले ही निपटाया गया है (`true`) या नहीं (`false`) |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | जब वस्तु निपटाई जाती है, तब होता है, ठीक संसाधनों के निपटान के सफलतापूर्वक पूर्ण होने के बाद |

### संबंधित देखें

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
