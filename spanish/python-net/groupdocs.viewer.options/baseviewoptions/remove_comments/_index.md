---
title: "propiedad remove_comments"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad deshabilita la renderización de comentarios cuando se establece en True."
type: docs
url: /es/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

La propiedad desactiva la renderización de comentarios cuando se establece en True. Por defecto es False, por lo que se muestran todos los comentarios.

Algunos formatos de documento como PDF y WordProcessing pueden contener comentarios. Por defecto, GroupDocs.Viewer los renderiza. Con esta opción establecida en True, los comentarios pueden excluirse del documento resultante.

Esta opción reemplaza la propiedad obsoleta `RenderComments`.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Ver también
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
