---
title: "FileLogger 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将日志消息写入文件。"
type: docs
url: /zh/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

将日志消息写入文件。

FileLogger 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | 初始化一个将消息写入文件的记录器。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | 将错误信息写入控制台。错误日志消息提供有关应用程序流程中不可恢复事件的信息。 |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | 将跟踪信息写入日志。跟踪日志消息提供有关应用程序流程的一般有用信息。 |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | 将警告信息写入控制台。 |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### 示例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### 另见
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
