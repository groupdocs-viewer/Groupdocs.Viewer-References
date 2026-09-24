---
title: error method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Writes an error message to the console."
type: docs
url: /python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Writes an error message to the console.

Error log messages provide information about unrecoverable events in application flow.

```python
def error(self, message, exception):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| message | `str` | The error message. |
| exception | `Exception` | The exception. |

| Raises | Description |
| :- | :- |
| `ValueError` | Thrown when `exception` is None. |

### See Also
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
