---
title: "propiedad fonts_to_exclude"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La lista de nombres de fuentes a excluir del documento HTML."
type: docs
url: /es/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

La lista de nombres de fuentes a excluir del documento HTML.

Las fuentes que se añaden al documento HTML mejoran la estabilidad de la vista de salida, al mismo tiempo que aumentan el tamaño del resultado del renderizado. Esta opción le permite equilibrar entre estabilidad y tamaño de salida. Incluya los nombres de fuentes que son populares y están instalados en la mayoría de los sistemas.

Tenga en cuenta que esta propiedad está activa solo cuando la opción [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) está deshabilitada.

Para obtener detalles y un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Ver también
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
