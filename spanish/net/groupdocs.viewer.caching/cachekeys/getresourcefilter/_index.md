---
title: "GetResourceFilter"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve la cadena de filtro para buscar entradas de caché que representan objetos Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 60
url: /es/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

Devuelve la cadena de filtro para buscar entradas de caché que representan objetos [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceFilter(int pageNumber)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de página. |

### Valor devuelto

Cadena de filtro para buscar entradas de caché que representan objetos [`Resource`](../../../groupdocs.viewer.results/resource).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzada cuando *pageNumber* es menor o igual a cero. |

### Ver también

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
