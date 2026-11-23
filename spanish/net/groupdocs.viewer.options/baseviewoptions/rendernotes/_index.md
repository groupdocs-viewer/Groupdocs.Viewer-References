---
title: "RenderNotes"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Habilita la representación de notas y anotaciones para algunos formatos."
type: docs
weight: 120
url: /es/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

Habilita la representación de notas y anotaciones para algunos formatos.

```csharp
public bool RenderNotes { get; set; }
```

### Observaciones

Algunos formatos, como presentaciones o archivos de Microsoft Project, pueden contener notas. Además, los archivos PDF pueden tener anotaciones emergentes (sugerencias en globo), que están ocultas de forma predeterminada y solo son visibles en un visor PDF al apuntar el cursor del ratón sobre ellas. De forma predeterminada, GroupDocs.Viewer no renderiza esas notas y anotaciones (`false`). Para hacerlo, establezca esta propiedad en `true`.

Para un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes).

### Ver también

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
