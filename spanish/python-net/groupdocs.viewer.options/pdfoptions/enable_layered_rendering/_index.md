---
title: "propiedad enable_layered_rendering"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad habilita el renderizado de texto y gráficos en el orden Z del documento PDF original al renderizar a HTML."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

La propiedad habilita el renderizado de texto y gráficos en el orden Z del documento PDF original al renderizar a HTML.

Por defecto, GroupDocs.Viewer renderiza texto y gráficos como una sola capa en HTML. Esta opción le permite organizar los objetos en el mismo orden que en el archivo de origen. El valor predeterminado es False.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
