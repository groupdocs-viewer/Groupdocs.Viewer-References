---
title: "GetResourceKey"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve el identificador único para la entrada de caché que representa el objeto Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 70
url: /es/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

Devuelve el identificador único para la entrada de caché que representa el objeto [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de la página. |
| resource | Recurso | El recurso HTML. |

### Valor devuelto

Identificador único para la entrada de caché que representa el objeto [`Resource`](../../../groupdocs.viewer.results/resource).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzada cuando *pageNumber* es menor o igual a cero. |
| ArgumentNullException | Se lanza cuando *resource* es nulo. |

### Ver también

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
