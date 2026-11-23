---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化用于渲染文字处理文档的选项。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化用于渲染文字处理文档的选项。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # 启用已跟踪更改的渲染。
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### 另见
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
