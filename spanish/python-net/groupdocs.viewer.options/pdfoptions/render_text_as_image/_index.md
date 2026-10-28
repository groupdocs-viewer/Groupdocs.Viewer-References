---
title: "propiedad render_text_as_image"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La opción habilita el renderizado de textos en archivos PDF como una imagen en la salida HTML."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

La opción habilita el renderizado de textos en archivos PDF como una imagen en la salida HTML.

Cuando esta opción está establecida en True, GroupDocs.Viewer renderiza el texto como una imagen en la salida HTML. Esto hace que el texto no sea seleccionable y mejora la renderización de los caracteres, garantizando una apariencia similar a PDF en HTML. El valor predeterminado es False.

Esta opción está disponible para renderizar a HTML.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
