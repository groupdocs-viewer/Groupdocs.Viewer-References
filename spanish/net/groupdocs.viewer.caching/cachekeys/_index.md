---
title: "CacheKeys"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Proporciona métodos para obtener el identificador único de la entrada de caché."
type: docs
weight: 980
url: /es/net/groupdocs.viewer.caching/cachekeys/
---

## CacheKeys class

Proporciona métodos para obtener el identificador único de la entrada de caché.

```csharp
public static class CacheKeys
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetAttachmentKey](../../groupdocs.viewer.caching/cachekeys/getattachmentkey)(string) | Devuelve el identificador único para la entrada de caché que representa el archivo adjunto. |
| static [GetAttachmentsKey](../../groupdocs.viewer.caching/cachekeys/getattachmentskey)() | Devuelve el identificador único para la entrada de caché que representa la colección de objetos [`Attachment`](../../groupdocs.viewer.results/attachment). |
| static [GetFileInfoKey](../../groupdocs.viewer.caching/cachekeys/getfileinfokey)() | Devuelve el identificador único para la entrada de caché que representa el objeto [`ViewInfo`](../../groupdocs.viewer.results/viewinfo). |
| static [GetFileKey](../../groupdocs.viewer.caching/cachekeys/getfilekey)(string) | Devuelve el identificador único para la entrada de caché que representa el archivo. |
| static [GetPageKey](../../groupdocs.viewer.caching/cachekeys/getpagekey)(int, string) | Devuelve el identificador único para la entrada de caché que representa el archivo de página. |
| static [GetResourceFilter](../../groupdocs.viewer.caching/cachekeys/getresourcefilter)(int) | Devuelve la cadena de filtro para buscar entradas de caché que representan objetos [`Resource`](../../groupdocs.viewer.results/resource). |
| static [GetResourceKey](../../groupdocs.viewer.caching/cachekeys/getresourcekey)(int, Resource) | Devuelve el identificador único para la entrada de caché que representa el objeto [`Resource`](../../groupdocs.viewer.results/resource). |
| static [GetViewInfoKey](../../groupdocs.viewer.caching/cachekeys/getviewinfokey)() | Devuelve el identificador único para la entrada de caché que representa el objeto [`ViewInfo`](../../groupdocs.viewer.results/viewinfo). |

### Ver también

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
