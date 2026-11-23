---
title: "Permissions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Define los permisos del documento PDF."
type: docs
weight: 430
url: /es/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

Define los permisos del documento PDF.

```csharp
[Flags]
public enum Permissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AllowAll | `0` | Permitir impresión, modificación y extracción de datos. |
| DenyPrinting | `1` | Denegar impresión. |
| DenyModification | `2` | Denegar la modificación de contenido, el relleno de formularios, la adición o modificación de anotaciones. |
| DenyDataExtraction | `4` | Denegar la extracción de texto y gráficos. |
| DenyAll | `7` | Denegar impresión, modificación de contenido y extracción de datos. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
