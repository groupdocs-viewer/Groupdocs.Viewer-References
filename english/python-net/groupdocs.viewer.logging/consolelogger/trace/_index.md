---
title: trace method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Writes a trace message to the console."
type: docs
url: /python-net/groupdocs.viewer.logging/consolelogger/trace/
is_root: false
weight: 1020
---


## trace {#message}

Writes a trace message to the console.

Trace log messages provide generally useful information about application flow.

```python
def trace(self, message):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| message | `str` | The trace message. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `message` is None. |

### Aliases

These names call `trace` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `trace_file` | `trace_file(message)` |
| `trace_string` | `trace_string(message)` |

### See Also
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
