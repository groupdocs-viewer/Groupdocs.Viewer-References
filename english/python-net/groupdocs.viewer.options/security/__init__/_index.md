---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the Security class."
type: docs
url: /python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Initializes an instance of the [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) class.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.viewer.options import Security, Permissions

# Create a security configuration.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### See Also
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
