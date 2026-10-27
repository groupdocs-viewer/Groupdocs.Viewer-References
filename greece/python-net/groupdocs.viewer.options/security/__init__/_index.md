---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία της κλάσης Security."
type: docs
url: /el/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια παρουσία της κλάσης [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer.options import Security, Permissions

# Δημιουργήστε μια διαμόρφωση ασφαλείας.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Δείτε επίσης
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
