---
title: "propiedad disable_chars_grouping"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad desactiva la agrupación de símbolos para un posicionamiento preciso de los símbolos durante el renderizado de la página."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

La propiedad desactiva la agrupación de símbolos para un posicionamiento preciso de los símbolos durante el renderizado de la página.

Al convertir archivos PDF, GroupDocs.Viewer agrupa caracteres individuales en palabras para mejorar el rendimiento del renderizado. Si su documento incluye jeroglíficos o símbolos especiales, es posible que desee prohibir el agrupamiento de caracteres para garantizar un diseño más preciso. El valor predeterminado es False.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
