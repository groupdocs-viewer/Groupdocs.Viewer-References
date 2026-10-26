---
title: "GetPageKey"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve el identificador único para la entrada de caché que representa el archivo de página."
type: docs
weight: 50
url: /es/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

Devuelve el identificador único para la entrada de caché que representa el archivo de página.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de la página. |
| extensión | String | El sufijo del nombre de archivo (incluyendo el punto ".") p. ej. ".doc". |

### Valor devuelto

Identificador único para la entrada de caché que representa el archivo de página.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzada cuando *pageNumber* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *extension* es nulo o está vacío. |

### Ver también

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
