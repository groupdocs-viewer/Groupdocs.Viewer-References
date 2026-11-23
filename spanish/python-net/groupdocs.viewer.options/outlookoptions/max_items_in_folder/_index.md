---
title: "propiedad max_items_in_folder"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "El número máximo de mensajes o elementos que se pueden renderizar desde una carpeta."
type: docs
url: /es/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

El número máximo de mensajes o elementos que se pueden renderizar desde una carpeta.

Los archivos de datos de Outlook pueden ser grandes y recuperar todos los mensajes puede llevar tiempo significativo. Esta propiedad limita el número máximo de mensajes o elementos que se renderizan. El valor predeterminado es `50`. Para renderizar todos los mensajes, establezca el valor en `0`.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### Ver también
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
