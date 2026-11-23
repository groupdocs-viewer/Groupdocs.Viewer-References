---
title: "IResourceStreamFactory"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "रिसोर्स URL बनाने, इंस्टैंसिएट करने और आउटपुट HTML रिसोर्स स्ट्रीम को रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है।"
type: docs
weight: 770
url: /hi/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

संसाधन URL बनाने, आउटपुट HTML संसाधन स्ट्रीम को इंस्टैंसिएट और रिलीज़ करने के लिए आवश्यक विधियों को परिभाषित करता है।

```csharp
public interface IResourceStreamFactory
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | आउटपुट HTML रिसोर्स डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम बनाता है। |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | HTML रिसोर्स के लिए URL बनाता है। |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | [`CreateResourceStream`](./createresourcestream) मेथड द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
