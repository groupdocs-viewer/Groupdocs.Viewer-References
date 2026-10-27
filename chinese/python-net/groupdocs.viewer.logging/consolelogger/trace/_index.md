---
title: "trace 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将跟踪信息写入控制台。"
type: docs
url: /zh/python-net/groupdocs.viewer.logging/consolelogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

将跟踪信息写入控制台。

跟踪日志消息提供有关应用程序流程的一般有用信息。

```python
def trace(self, message):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| message | `str` | 跟踪消息。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `message` 为 None 时抛出。 |

### 另见
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
