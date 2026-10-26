---
title: "VerticalResolution"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Obtiene o establece la resolución vertical para las imágenes generadas en puntos por pulgada. Esta opción se usa al renderizar documentos WordProcessing a formatos PNG o JPEG únicamente."
type: docs
weight: 130
url: /es/net/groupdocs.viewer.options/wordprocessingoptions/verticalresolution/
---

## WordProcessingOptions.VerticalResolution property

Obtiene o establece la resolución vertical para las imágenes generadas en puntos por pulgada. Esta opción se usa al renderizar documentos WordProcessing a formatos PNG o JPEG únicamente.

```csharp
public int VerticalResolution { get; set; }
```

### Observaciones

El valor predeterminado es 96 DPI. El valor mínimo posible es 72 DPI, el valor máximo posible es 600 DPI. Si el valor especificado por el usuario está fuera de estos límites, se aplicará el valor mínimo o máximo posible.

### Ver también

* class [WordProcessingOptions](../../wordprocessingoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
