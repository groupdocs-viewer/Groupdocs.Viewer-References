---
title: "ConsoleLogger 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将日志消息写入控制台。"
type: docs
url: /zh/python-net/groupdocs.viewer.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

将日志消息写入控制台。

ConsoleLogger 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/consolelogger/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error/#message-exception) | 将错误信息写入控制台。 |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace/#message) | 将跟踪信息写入控制台。 |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning/#message) | 将警告信息写入控制台。 |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_string/) |  |

### 示例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### 另见
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
