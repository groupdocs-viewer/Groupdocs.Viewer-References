---
title: "error 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将错误信息写入控制台。"
type: docs
url: /zh/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

将错误信息写入控制台。错误日志消息提供有关应用程序流程中不可恢复事件的信息。

```python
def error(self, message, exception):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| message | `str` | 错误消息。 |
| exception | `Exception` | 异常。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `exception` 为 None 时。 |

### 另见
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
