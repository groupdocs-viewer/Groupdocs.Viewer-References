---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة من الفئة Security."
type: docs
url: /ar/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

يُهيء مثيلاً من الفئة [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer.options import Security, Permissions

# إنشاء تكوين أمان.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### انظر أيضًا
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
