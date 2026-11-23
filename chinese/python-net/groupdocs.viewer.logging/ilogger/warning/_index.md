---
title: "warning 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "写入警告信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.logging/ilogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

写入警告信息。

Warning 日志消息提供有关应用程序流程中意外且可恢复事件的信息。

```python
def warning(self, message):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| message | `str` | 警告消息。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `message` 为 None 时。 |

### 另见
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
