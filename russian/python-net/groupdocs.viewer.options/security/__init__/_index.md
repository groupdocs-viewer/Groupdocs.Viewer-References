---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса Security."
type: docs
url: /ru/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует экземпляр класса [`Security`](/viewer/python-net/groupdocs.viewer.options/security/).

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.viewer.options import Security, Permissions

# Создайте конфигурацию безопасности.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### См. также
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
