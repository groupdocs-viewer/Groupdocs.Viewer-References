---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "प्रोसेस किए गए MB की मात्रा प्राप्त करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

प्रोसेस किए गए MB की मात्रा प्राप्त करता है।

```csharp
public static decimal GetConsumptionQuantity()
```

### उदाहरण

निम्न उदाहरण दर्शाता है कि प्रोसेस किए गए MB की मात्रा कैसे प्राप्त करें।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### संबंधित देखें

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
