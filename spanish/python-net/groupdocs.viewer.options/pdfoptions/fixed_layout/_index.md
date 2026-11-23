---
title: "propiedad fixed_layout"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La opción de diseño fijo habilita el renderizado de documentos PDF y EPUB a HTML con un diseño fijo."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

La opción de diseño fijo habilita el renderizado de documentos PDF y EPUB a HTML con un diseño fijo.

Los documentos PDF y EPUB se renderizan inicialmente a HTML con un diseño fijo para mantener la apariencia del documento original. Este diseño fijo significa que todos los elementos HTML tienen posiciones precisas dentro de un contenedor con un tamaño establecido. Cambiar el tamaño de la ventana del navegador no afecta la posición ni el tamaño de los elementos en el documento.

Esta opción solo está disponible al renderizar a HTML. El valor predeterminado es `True`. Para renderizar con un diseño fluido, establezca esta propiedad en `False`.

Al renderizar con diseño fluido, se omiten las imágenes. Utilice el diseño fluido al renderizar documentos PDF con contenido de texto.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
