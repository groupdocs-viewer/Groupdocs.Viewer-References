---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas Security."
type: docs
url: /id/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance dari kelas [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer.options import Security, Permissions

# Buat konfigurasi keamanan.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### Lihat Juga
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
