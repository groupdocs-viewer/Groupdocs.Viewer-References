---
title: "for_png_view 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个 ViewInfoOptions 类的实例，以在渲染为 PNG 时检索视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

初始化一个 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 类的实例，以在渲染为 PNG 时检索视图信息。

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# 为 PNG 格式创建视图信息选项
view_info_options_png = ViewInfoOptions.for_png_view()

# 加载文档并获取 PNG 的视图信息
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

初始化一个 ViewInfoOptions 类的实例，以在渲染为 PNG 时检索视图信息。

```python
def for_png_view(cls, extract_text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extract_text | `bool` | 启用文本提取。 |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 示例

```python
from groupdocs.viewer.options import ViewInfoOptions

# 为启用文本提取的 PNG 格式创建视图信息选项
options = ViewInfoOptions.for_png_view(extractText=True)
```

### 另见
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
