---
title: "propiedad render_original_page_size"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "El tamaño de página de salida se establece para coincidir con el tamaño de página del documento PDF fuente."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

El tamaño de página de salida se establece para coincidir con el tamaño de página del documento PDF fuente.

Por defecto, GroupDocs.Viewer calcula el tamaño de página de la imagen de salida para una mejor calidad de renderizado. Active esta opción para garantizar que las páginas de salida tengan el mismo tamaño que el tamaño de página del documento PDF de origen (en píxeles). El valor predeterminado es False.

Esta opción está disponible para renderizar a formatos PNG o JPG.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
