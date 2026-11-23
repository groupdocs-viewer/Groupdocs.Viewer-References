---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Security-Klasse."
type: docs
url: /de/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine Instanz der [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) Klasse.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.viewer.options import Security, Permissions

# Erstelle eine Sicherheitskonfiguration.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Siehe auch
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
