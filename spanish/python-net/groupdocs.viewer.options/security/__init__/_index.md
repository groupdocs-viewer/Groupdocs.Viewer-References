---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase Security."
type: docs
url: /es/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una instancia de la clase [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer.options import Security, Permissions

# Crea una configuración de seguridad.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Ver también
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
