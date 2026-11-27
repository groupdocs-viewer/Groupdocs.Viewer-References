---
title: warning method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Writes a warning message to the console."
type: docs
url: /python-net/groupdocs.viewer.logging/consolelogger/warning/
is_root: false
weight: 1030
---


## warning {#message}

Writes a warning message to the console.

Warning log messages provide information about unexpected and recoverable events in application flow.

```python
def warning(self, message):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| message | `str` | The warning message. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `message` is None. |

### Aliases

These names call `warning` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `warning_file` | `warning_file(message)` |
| `warning_string` | `warning_string(message)` |

### See Also
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
