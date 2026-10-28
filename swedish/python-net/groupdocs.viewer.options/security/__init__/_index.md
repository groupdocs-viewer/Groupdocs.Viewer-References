---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av klassen Security."
type: docs
url: /sv/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Initialiserar en instans av [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) klassen.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.viewer.options import Security, Permissions

# Skapa en säkerhetskonfiguration.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Se även
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
