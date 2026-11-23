---
title: "propiedad horizontal_resolution"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La resolución horizontal para imágenes generadas en puntos por pulgada."
type: docs
url: /es/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

La resolución horizontal para imágenes generadas en puntos por pulgada. Esta opción se usa solo al renderizar documentos WordProcessing a formatos PNG o JPEG.

El valor predeterminado es 96 DPI. El valor mínimo posible es 72 DPI; el valor máximo posible es 600 DPI. Si un valor especificado por el usuario está fuera de estos límites, se aplicará el límite más cercano (mínimo o máximo).

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Ver también
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
