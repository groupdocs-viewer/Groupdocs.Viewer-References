---
title: "ViewerSettings 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "定义用于自定义 Viewer 行为的设置。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

定义用于自定义 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 行为的设置。

ViewerSettings 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | 初始化一个新的 ViewerSettings 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | 初始化一个新的 ViewerSettings 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | 初始化一个新的 ViewerSettings 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | 用于存储渲染结果的缓存实现。 |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | 用于记录（错误、警告、跟踪）的日志实现。 |

### 示例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### 另见
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
