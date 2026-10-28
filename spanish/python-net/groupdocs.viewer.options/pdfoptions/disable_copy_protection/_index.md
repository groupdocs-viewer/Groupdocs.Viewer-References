---
title: "propiedad disable_copy_protection"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad desactiva la protección contra copia de contenido al renderizar a HTML."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

La propiedad desactiva la protección contra copia de contenido al renderizar a HTML.

Al renderizar archivos PDF con protección contra la copia de texto e imágenes a HTML, GroupDocs.Viewer agrega un atributo HTML `inert` a la etiqueta BODY del HTML. El valor predeterminado es `False`, lo que significa que el atributo `inert` se agrega solo si el documento PDF está protegido.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
