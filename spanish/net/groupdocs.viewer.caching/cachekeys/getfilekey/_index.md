---
title: "GetFileKey"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve el identificador único para la entrada de caché que representa el archivo."
type: docs
weight: 40
url: /es/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

Devuelve el identificador único para la entrada de caché que representa el archivo.

```csharp
public static string GetFileKey(string extension)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| extensión | String | El sufijo del nombre de archivo (incluyendo el punto ".") p. ej. ".doc". |

### Valor devuelto

Identificador único para la entrada de caché que representa el archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *extension* es nulo o está vacío. |

### Ver también

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
