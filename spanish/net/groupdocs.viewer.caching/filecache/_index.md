---
title: "FileCache"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa una caché local en disco."
type: docs
weight: 990
url: /es/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Representa una caché local en disco.

```csharp
public class FileCache : ICache
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileCache](filecache#constructor)(string) | Crea una nueva instancia de la clase [`FileCache`](../filecache). |
| [FileCache](filecache#constructor_1)(string, string) | Crea una nueva instancia de la clase [`FileCache`](../filecache). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | La ruta relativa o absoluta a la carpeta de caché. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | La subcarpeta que se añadirá a [`CachePath`](./cachepath). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | Devuelve todos los nombres de archivo que contienen el filtro en el nombre del archivo. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | Serializa los datos al disco local. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | Deserializa los datos asociados a esta clave si están presentes. |

### Ver también

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
