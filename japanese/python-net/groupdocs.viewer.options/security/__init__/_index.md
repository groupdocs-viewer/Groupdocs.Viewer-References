---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Security クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

[`Security`](/viewer/python-net/groupdocs.viewer.options/security/) クラスのインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer.options import Security, Permissions

# セキュリティ構成を作成します。
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### 参照
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
