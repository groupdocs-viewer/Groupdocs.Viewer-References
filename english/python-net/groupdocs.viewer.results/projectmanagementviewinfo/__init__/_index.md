---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of ProjectManagementViewInfo."
type: docs
url: /python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Initializes a new instance of ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file. |
| pages | `List[Page]` | The list of pages to view. |
| start_date | `datetime` | The date time from which the project started. |
| end_date | `datetime` | The date time when the project is to be completed. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `pages` is None. |

### See Also
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
