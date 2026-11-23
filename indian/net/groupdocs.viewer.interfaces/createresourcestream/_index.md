---
title: "CreateResourceStream"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि को दर्शाता है।"
type: docs
weight: 720
url: /hi/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि को दर्शाता है।

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | Int32 | पृष्ठ की संख्या। |
| संसाधन | संसाधन | फ़ॉन्ट, शैली, छवि या ग्राफ़िक्स जैसे HTML संसाधन। |

### वापसी मान

आउटपुट HTML रिसोर्स डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम।

### संबंधित देखें

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
