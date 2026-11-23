---
title: "propiedad max_items"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "El número máximo de mensajes o elementos a renderizar."
type: docs
url: /es/python-net/groupdocs.viewer.options/mailstorageoptions/max_items/
is_root: false
weight: 2020
---


## max_items property

El número máximo de mensajes o elementos a renderizar.

Los archivos de datos de almacenamiento de correo pueden ser grandes y recuperar todos los mensajes puede llevar tiempo significativo. Esta propiedad limita el número máximo de mensajes o elementos que se renderizan. El valor predeterminado es 0 – se renderizan todos los mensajes.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def max_items(self):
    ...
@max_items.setter
def max_items(self, value):
    ...
```

### Ver también
* class [`MailStorageOptions`](/viewer/python-net/groupdocs.viewer.options/mailstorageoptions/)
