---
title: "TryGetValue"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Obtiene la entrada asociada a esta clave si está presente."
type: docs
weight: 30
url: /es/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

Obtiene la entrada asociada a esta clave si está presente.

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| Parámetro | Descripción |
| --- | --- |
| TEntry | Tipo de entrada. |
| clave | Una clave que identifica la entrada solicitada. |
| value | El valor localizado o nulo. |

### Valor devuelto

```csharp
True
```

si se encontró la clave.

### Ver también

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
