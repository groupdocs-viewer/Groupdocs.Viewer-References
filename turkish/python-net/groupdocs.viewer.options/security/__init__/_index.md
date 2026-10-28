---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Security sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

[`Security`](/viewer/python-net/groupdocs.viewer.options/security/) sınıfının bir örneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer.options import Security, Permissions

# Bir güvenlik yapılandırması oluşturun.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Ayrıca Bakınız
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
