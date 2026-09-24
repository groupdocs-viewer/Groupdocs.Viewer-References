---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of LotusNotesViewInfo."
type: docs
url: /python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Initializes a new instance of the [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) class.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file. |
| pages | `List[Page]` | The list of pages to view. |
| notes_count | `int` | The notes count contained by the Lotus database storage file. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `notes_count` is None. |

### See Also
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
