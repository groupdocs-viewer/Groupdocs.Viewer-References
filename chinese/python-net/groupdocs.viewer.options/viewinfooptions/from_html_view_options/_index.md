---
title: "from_html_view_options 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "基于 HtmlViewOptions 对象初始化一个 ViewInfoOptions 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

基于 HtmlViewOptions 对象初始化一个 ViewInfoOptions 类的实例。

```python
def from_html_view_options(cls, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `HtmlViewOptions` | HTML 视图选项。 |

**Returns:** A new ViewInfoOptions instance.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `options` 为 None。 |

### 示例

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### 另见
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
