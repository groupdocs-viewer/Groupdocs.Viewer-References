---
title: "for_jpg_view 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个 ViewInfoOptions 实例，以在渲染为 JPG 时检索视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

初始化一个 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 实例，以在渲染为 JPG 时检索视图信息。

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

初始化一个 ViewInfoOptions 实例，以在渲染为 JPG 时检索视图信息。

```python
def for_jpg_view(cls, extract_text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extract_text | `bool` | 启用文本提取。 |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 另见
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
