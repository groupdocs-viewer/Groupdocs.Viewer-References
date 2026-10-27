---
title: "dispose 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "释放文件流和受管理的内部资源。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/dispose/
is_root: false
weight: 1010
---


## dispose

释放文件流和受管理的内部资源。

```python
def dispose(self):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer

viewer = Viewer("./sample.docx")
# 使用查看器执行操作
viewer.dispose()
```

### 另见
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
