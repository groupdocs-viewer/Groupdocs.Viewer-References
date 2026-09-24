---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new PdfViewInfo instance."
type: docs
url: /python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new PdfViewInfo instance.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Initializes a new PdfViewInfo instance.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file. |
| pages | `List[Page]` | The list of pages to view. |
| printing_allowed | `bool` | The printing permission indicator. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `pages` is None. |

### See Also
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
