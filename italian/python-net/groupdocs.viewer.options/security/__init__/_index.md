---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe Security."
type: docs
url: /it/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza un'istanza della classe [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.viewer.options import Security, Permissions

# Crea una configurazione di sicurezza.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Vedi anche
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
