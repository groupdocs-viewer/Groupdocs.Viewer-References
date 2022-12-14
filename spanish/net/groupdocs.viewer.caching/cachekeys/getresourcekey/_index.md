---
title: GetResourceKey
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Devuelve un identificador único para la entrada de caché que representaResourcegroupdocs.viewer.results/resource objeto.
type: docs
weight: 70
url: /es/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---
## CacheKeys.GetResourceKey method

Devuelve un identificador único para la entrada de caché que representa[`Resource`](../../../groupdocs.viewer.results/resource) objeto.

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de la página. |
| resource | Resource | El recurso HTML. |

### Valor_devuelto

Identificador único para la entrada de caché que representa[`Resource`](../../../groupdocs.viewer.results/resource) objeto.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*pageNumber* es menor o igual a cero. |
| ArgumentNullException | arrojado cuando*resource* es nulo. |

### Ver también

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* espacio de nombres [GroupDocs.Viewer.Caching](../../cachekeys)
* asamblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
