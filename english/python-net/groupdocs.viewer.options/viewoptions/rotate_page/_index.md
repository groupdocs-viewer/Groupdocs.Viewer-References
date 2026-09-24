---
title: rotate_page method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Applies the clockwise rotation to a page."
type: docs
url: /python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Applies the clockwise rotation to a page.

For details, see the documentation at https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The page number, must be strictly greater than 0. |
| rotation | `Rotation` | The rotation value. |

| Raises | Description |
| :- | :- |
| `ValueError` | If rotation for the page with number `page_number` was already added. |

### See Also
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
