---
title: "FileCache"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Crea una nueva instancia de la clase FileCachegroupdocs.viewer.caching/filecache."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.caching/filecache/filecache/
---

## FileCache(string) {#constructor}

Crea una nueva instancia de la clase [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| cachePath | String | Ruta relativa o absoluta donde se almacenará la caché del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *cachePath* es nulo. |

### Ver también

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

Crea una nueva instancia de la clase [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| cachePath | String | Ruta relativa o absoluta donde se almacenará la caché del documento. |
| cacheSubFolder | String | La subcarpeta que se agrega a *cachePath*. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *cachePath* es nulo. |
| ArgumentNullException | Se lanza cuando *cacheSubFolder* es nulo. |

### Ver también

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
