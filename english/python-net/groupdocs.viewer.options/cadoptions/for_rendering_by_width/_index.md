---
title: for_rendering_by_width method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the CadOptions class for rendering by width."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by width.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | `int` | The width of the output result (in pixels). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Raises | Description |
| :- | :- |
| `ValueError` | If `width` is less than or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Load CAD file
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
