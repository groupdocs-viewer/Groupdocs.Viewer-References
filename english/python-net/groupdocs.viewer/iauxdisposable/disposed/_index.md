---
title: disposed event
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Occurs when object is disposed, right after the resources disposing is successfully completed"
type: docs
url: /python-net/groupdocs.viewer/iauxdisposable/disposed/
is_root: false
weight: 4010
---


## disposed event

Occurs when object is disposed, right after the resources disposing is successfully completed

### Definition:
```python
i_aux_disposable.disposed += handler    # subscribe handler(sender, args)
i_aux_disposable.disposed -= handler    # remove the last subscription of handler
i_aux_disposable.disposed.clear()       # remove every handler added from Python
```

### Handler arguments
| Argument | Description |
| :- | :- |
| `sender` | The object that raised the event. |
| `args` | the event's data, if any |

The handler runs on the thread that raises the event, which can be an engine worker thread. An exception it raises there is printed to stderr and ignored; on the calling thread it reaches the engine, as in .NET.

### See Also
* class [`IAuxDisposable`](/viewer/python-net/groupdocs.viewer/iauxdisposable/)
