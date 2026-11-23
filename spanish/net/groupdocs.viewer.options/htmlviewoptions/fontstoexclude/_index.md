---
title: "FontsToExclude"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "La lista de nombres de fuentes a excluir del documento HTML."
type: docs
weight: 40
url: /es/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---

## HtmlViewOptions.FontsToExclude property

La lista de nombres de fuentes a excluir del documento HTML.

```csharp
public List<string> FontsToExclude { get; set; }
```

### Observaciones

Las fuentes que se añaden al documento HTML mejoran la estabilidad de la vista de salida, al mismo tiempo que aumentan el tamaño del resultado renderizado. Esta opción le permite equilibrar entre estabilidad y tamaño de salida. Incluya los nombres de fuentes que son populares y están instalados en la mayoría de los sistemas.

Tenga en cuenta que esta propiedad está activa solo cuando la opción [`ExcludeFonts`](../excludefonts) está deshabilitada.

Para obtener más detalles y un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/exclude-fonts/).

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
