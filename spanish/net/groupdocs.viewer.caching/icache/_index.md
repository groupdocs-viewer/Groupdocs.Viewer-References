---
title: "ICache"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Define los métodos requeridos para almacenar el documento renderizado y los recursos del documento en caché."
type: docs
weight: 1000
url: /es/net/groupdocs.viewer.caching/icache/
---

## ICache interface

Define los métodos requeridos para almacenar el documento renderizado y los recursos del documento en caché.

```csharp
public interface ICache
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | Devuelve todas las claves que coinciden con el filtro. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | Inserta una entrada de caché en la caché. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | Obtiene la entrada asociada a esta clave si está presente. |

### Ver también

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
