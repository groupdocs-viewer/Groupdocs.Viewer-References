---
title: search method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Performs a text search and highlights the found text in the loaded document according to the provided options."
type: docs
url: /python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Performs a text search and highlights the found text in the loaded document according to the provided options.

```python
def search(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Search and highlight options, including the text phrase to search. Must not be None. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `options` is None. |

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
