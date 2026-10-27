---
title: "ViewInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示通用文档的视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

表示通用文档的视图信息。

ViewInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | 初始化一个新的 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | 初始化一个新的 ViewInfo 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 返回表示当前对象的字符串。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 文件的类型。 |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 要查看的页面列表。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
