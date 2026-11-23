---
title: "SetMeteredKey"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Metered कुंजियों के साथ उत्पाद को सक्रिय करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

Metered कुंजियों के साथ उत्पाद को सक्रिय करता है।

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | String | सार्वजनिक कुंजी। |
| privateKey | String | निजी कुंजी। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि मीटर कीज़ के साथ उत्पाद को कैसे सक्रिय करें।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### संबंधित देखें

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
