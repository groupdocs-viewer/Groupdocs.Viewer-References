---
title: "GetConsumptionQuantity"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Recupera la cantidad de MB procesados."
type: docs
weight: 40
url: /es/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

Recupera la cantidad de MB procesados.

```csharp
public static decimal GetConsumptionQuantity()
```

### Ejemplos

El siguiente ejemplo demuestra cómo obtener la cantidad de MB procesados.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
