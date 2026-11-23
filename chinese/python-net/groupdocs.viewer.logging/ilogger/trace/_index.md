---
title: "trace 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "写入跟踪信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

写入跟踪信息。

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
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
