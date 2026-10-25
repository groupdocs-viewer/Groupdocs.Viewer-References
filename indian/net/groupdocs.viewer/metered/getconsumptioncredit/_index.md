---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "उपयोग किए गए क्रेडिट की संख्या प्राप्त करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.viewer/metered/getconsumptioncredit/
---

## Metered.GetConsumptionCredit method

उपयोग किए गए क्रेडिट की संख्या प्राप्त करता है।

```csharp
public static decimal GetConsumptionCredit()
```

### उदाहरण

निम्न उदाहरण दिखाता है कि कैसे उपयोग किए गए क्रेडिट की संख्या प्राप्त की जाए।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### संबंधित देखें

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
