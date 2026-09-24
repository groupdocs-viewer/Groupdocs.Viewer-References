---
title: for_rendering_by_height method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a CadOptions instance for rendering by height."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Initializes a CadOptions instance for rendering by height.

For code example, see the documentation.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| height | `int` | The height of the output result (in pixels). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Raises | Description |
| :- | :- |
| `ValueError` | When `height` is less than or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
