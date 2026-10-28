---
title: "propiedad wrap_images_in_svg"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad que habilita envolver cada imagen en el documento HTML de salida en una etiqueta SVG para mejorar la calidad de salida."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

La propiedad que habilita envolver cada imagen en el documento HTML de salida en una etiqueta SVG para mejorar la calidad de salida.

Por defecto, al renderizar archivos PDF y de diseño de página a HTML, todas las imágenes se renderizan como una única imagen PNG. La imagen PNG renderizada se utiliza como fondo del documento HTML de salida.

Esta opción está disponible al renderizar formatos de archivo PDF y de diseño de página a HTML con recursos incrustados y externos. Permite envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG. El valor predeterminado es False.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
