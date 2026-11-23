---
title: "RemoveComments"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Desactiva la renderización de comentarios cuando se establece en true. De forma predeterminada es false, todos los comentarios se muestran."
type: docs
weight: 100
url: /es/net/groupdocs.viewer.options/baseviewoptions/removecomments/
---

## BaseViewOptions.RemoveComments property

Desactiva la representación de comentarios cuando se establece en `true`. Por defecto es `false` — se muestran todos los comentarios.

```csharp
public bool RemoveComments { get; set; }
```

### Observaciones

Algunos formatos de documento como PDF y WordProcessing pueden contener comentarios. De forma predeterminada, GroupDocs.Viewer los renderiza. Con esta opción establecida en `true` los comentarios pueden excluirse del documento resultante.

Esta opción reemplaza la obsoleta propiedad 'RenderComments'.

### Ver también

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
