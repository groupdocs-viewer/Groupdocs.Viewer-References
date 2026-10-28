---
title: "propiedad vertical_resolution"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La resolución vertical para imágenes generadas en puntos por pulgada, usada solo al renderizar documentos WordProcessing a formatos PNG o JPEG."
type: docs
url: /es/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/
is_root: false
weight: 2120
---


## vertical_resolution property

La resolución vertical para imágenes generadas en puntos por pulgada, usada solo al renderizar documentos WordProcessing a formatos PNG o JPEG.

El valor predeterminado es 96 DPI.

El valor mínimo posible es 72 DPI y el valor máximo posible es 600 DPI. Si un valor especificado por el usuario está fuera de estos límites, se aplicará el límite más cercano.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### Ver también
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
