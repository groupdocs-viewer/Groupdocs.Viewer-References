---
title: "for_html_view 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个 ViewInfoOptions 实例，以在渲染为 HTML 时检索视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

初始化一个 ViewInfoOptions 实例，以在渲染为 HTML 时检索视图信息。

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### 示例

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # 为 HTML 格式（单页）创建视图信息选项
    options = ViewInfoOptions.for_html_view(True)

    # 加载文档并检索视图信息
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

初始化一个 ViewInfoOptions 实例，以在渲染为 HTML 时检索视图信息。

```python
def for_html_view(cls, render_single_page):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| render_single_page | `bool` | 启用将 HTML 内容渲染为单页。 |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# 检索单页 HTML 的视图信息
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### 另见
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
