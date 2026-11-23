---
title: "ReleasePageStream"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "रिलीज़ करता है वह स्ट्रीम जो CreatePageStream./createpagestream डेलीगेट से संबंधित मेथड द्वारा इंस्टैंशिएट किया गया था।"
type: docs
weight: 710
url: /hi/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

रिलीज़ करता है वह स्ट्रीम जो [`CreatePageStream`](../createpagestream) डेलीगेट से संबंधित मेथड द्वारा इंस्टैंशिएट किया गया था।

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |
| pageStream | Stream | स्ट्रीम जो [`CreatePageStream`](../createpagestream) डेलीगेट से संबंधित मेथड द्वारा बनाई गई है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
