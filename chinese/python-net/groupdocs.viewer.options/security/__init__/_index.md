---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Security 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) 类的实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer.options import Security, Permissions

# 创建安全配置。
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### 另见
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
