---
title: "GetAttachmentKey"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve el identificador único para la entrada de caché que representa el archivo adjunto."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

Devuelve el identificador único para la entrada de caché que representa el archivo adjunto.

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| attachmentId | String | Identificador único (en el contexto de un solo archivo) del adjunto. |

### Valor devuelto

Identificador único para la entrada de caché que representa el archivo adjunto.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *attachmentId* es nulo o está vacío. |

### Ver también

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
