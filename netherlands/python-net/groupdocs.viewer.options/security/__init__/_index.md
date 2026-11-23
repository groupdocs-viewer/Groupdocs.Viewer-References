---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de Security-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een instantie van de [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer.options import Security, Permissions

# Maak een beveiligingsconfiguratie.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Zie ook
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
