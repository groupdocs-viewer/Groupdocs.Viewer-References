---
title: "RenderOriginalPageSize"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Establece el tamaño de página de salida igual al tamaño de página del documento PDF de origen."
type: docs
weight: 90
url: /es/net/groupdocs.viewer.options/pdfoptions/renderoriginalpagesize/
---

## PdfOptions.RenderOriginalPageSize property

Establece el tamaño de página de salida igual al tamaño de página del documento PDF fuente.

```csharp
public bool RenderOriginalPageSize { get; set; }
```

### Observaciones

Por defecto, GroupDocs.Viewer calcula el tamaño de página de la imagen de salida para una mejor calidad de renderizado. Habilite esta opción para asegurar que las páginas de salida tengan el mismo tamaño que el tamaño de página del documento PDF de origen (en píxeles). El valor predeterminado es `false`.

Esta opción está disponible para renderizar a formatos PNG o JPG.

Para un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#preserve-the-size-of-document-pages).

### Ver también

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
