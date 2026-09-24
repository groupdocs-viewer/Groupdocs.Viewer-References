---
title: get_view_info method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns view and document specific information."
type: docs
url: /python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Returns view and document specific information.

Learn more about document - file type, pages count and other format specific properties:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewInfoOptions` | The view info options. |

**Returns:** Information about view and document specific information.

| Raises | Description |
| :- | :- |
| `ValueError` | When `options` is None. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
