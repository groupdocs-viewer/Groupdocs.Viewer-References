---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Watermark 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

初始化 [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) 类的实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 水印文本。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `text` 为 None 或为空。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

with Viewer("sample.docx") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "add_text_watermark/output-watermark.html"
    )
    view_options.watermark = Watermark("This is a watermark")
    viewer.view(view_options)
```

### 另见
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
