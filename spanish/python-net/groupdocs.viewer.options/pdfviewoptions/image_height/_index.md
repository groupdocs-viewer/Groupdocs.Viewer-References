---
title: "propiedad image_height"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La altura de una imagen de salida en píxeles."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

La altura de una imagen de salida en píxeles.

Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad al renderizar una sola imagen solo a HTML. Para obtener más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Si establece esta propiedad, la propiedad [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) se ignora.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Ver también
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
