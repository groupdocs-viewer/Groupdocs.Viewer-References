---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe Security."
type: docs
url: /fr/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une instance de la classe [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer.options import Security, Permissions

# Créez une configuration de sécurité.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Voir aussi
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
