---
title: "SetMeteredKey"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Activa el producto con claves Metered."
type: docs
weight: 20
url: /es/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

Activa el producto con claves Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| publicKey | String | La clave pública. |
| privateKey | String | La clave privada. |

### Ejemplos

El siguiente ejemplo demuestra cómo activar el producto con Metered keys.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
