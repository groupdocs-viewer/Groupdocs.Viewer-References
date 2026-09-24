---
title: from_html_view_options method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the ViewInfoOptions class based on the HtmlViewOptions object."
type: docs
url: /python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Initializes an instance of the ViewInfoOptions class based on the HtmlViewOptions object.

```python
def from_html_view_options(cls, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `HtmlViewOptions` | The HTML view options. |

**Returns:** A new ViewInfoOptions instance.

| Raises | Description |
| :- | :- |
| `ValueError` | If `options` is None. |

### Example

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### See Also
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
