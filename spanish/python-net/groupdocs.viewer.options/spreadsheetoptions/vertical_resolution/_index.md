---
title: "propiedad vertical_resolution"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La resolución vertical para las imágenes generadas en puntos por pulgada."
type: docs
url: /es/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

La resolución vertical para imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al representar hojas de cálculo en formatos PNG o JPEG.

El valor predeterminado es 96 DPI. El valor mínimo posible es 72 DPI; el valor máximo posible es 600 DPI. Si un valor especificado por el usuario está fuera de estos límites, se aplicará el límite más cercano.

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
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
