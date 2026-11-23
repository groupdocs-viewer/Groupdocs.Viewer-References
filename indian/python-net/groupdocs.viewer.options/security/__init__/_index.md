---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Security क्लास का एक उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

[`Security`](/viewer/python-net/groupdocs.viewer.options/security/) क्लास का एक उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer.options import Security, Permissions

# एक सुरक्षा कॉन्फ़िगरेशन बनाएं।
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### साथ में देखें
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
