---
title: "FileName 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "文件名."
type: docs
url: /zh/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

文件名.

FileName 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | 初始化 [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) 类的实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | 返回表示当前对象的字符串。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | 空文件名。 |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | 源文件的名称。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
