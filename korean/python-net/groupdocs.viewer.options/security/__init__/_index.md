---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Security 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/security/__init__/
is_root: false
weight: 10
---


## __init__

[`Security`](/viewer/python-net/groupdocs.viewer.options/security/) 클래스의 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.viewer.options import Security, Permissions

# 보안 구성을 생성합니다.
security = Security()
security.document_open_password = "open123"
security.permissions_password = "perm123"
security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING
```

### 참고
* class [`Security`](/viewer/python-net/groupdocs.viewer.options/security/)
