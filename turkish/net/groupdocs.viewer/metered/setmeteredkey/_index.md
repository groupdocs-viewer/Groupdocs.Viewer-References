---
title: "SetMeteredKey"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Metered anahtarlarla ürünü etkinleştirir."
type: docs
weight: 20
url: /tr/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

Metered anahtarlarla ürünü etkinleştirir.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| publicKey | String | Açık anahtar. |
| privateKey | String | Özel anahtar. |

### Örnekler

Aşağıdaki örnek, Metered anahtarlarla ürünün nasıl etkinleştirileceğini gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Ayrıca Bakınız

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
