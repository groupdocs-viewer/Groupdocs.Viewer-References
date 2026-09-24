---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of ArchiveViewInfo."
type: docs
url: /python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initializes a new ArchiveViewInfo instance.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file. |
| pages | `List[Page]` | The list of pages to view. |
| folders | `List[str]` | The list of folders contained by the archive file. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `folders` is None. |

### See Also
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
