---
title: "remove_unused_objects propiedad"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad elimina objetos no utilizados (huérfanos) de un archivo PDF."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

La propiedad elimina objetos no utilizados (huérfanos) de un archivo PDF.

Estos objetos se colocan en el documento PDF pero no están referenciados en los diccionarios de recursos de ninguna página y, por lo tanto, no se utilizan en absoluto. Activar esta propiedad (`True`) reducirá el tamaño del documento PDF de salida. Por defecto está desactivada (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Ver también
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
