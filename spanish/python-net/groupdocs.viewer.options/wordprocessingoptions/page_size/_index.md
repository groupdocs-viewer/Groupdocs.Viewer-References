---
title: "propiedad page_size"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "El tamaño de la página de salida."
type: docs
url: /es/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

El tamaño de la página de salida.

El valor predeterminado es `PageSize.Unspecified`, lo que significa que se utiliza un tamaño de página establecido en la configuración de página (Page Setup).

Al renderizar archivos HTM y HTML, el tamaño de página predeterminado se establece en Letter 792 x 612 puntos.

Como resultado, parte del contenido puede no caber en el marco de la página.

Establezca un tamaño de página mayor, por ejemplo `PageSize.A3`, para que el contenido quepa.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Ver también
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
