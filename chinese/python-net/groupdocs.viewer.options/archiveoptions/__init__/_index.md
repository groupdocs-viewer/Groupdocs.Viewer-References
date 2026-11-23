---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 ArchiveOptions 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/archiveoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) 类的实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/specific_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### 另见
* class [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/)
