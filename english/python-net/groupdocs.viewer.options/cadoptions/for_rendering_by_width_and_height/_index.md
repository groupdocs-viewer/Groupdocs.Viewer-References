---
title: for_rendering_by_width_and_height method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the CadOptions class for rendering by width and height."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/
is_root: false
weight: 1040
---


## for_rendering_by_width_and_height {#width-height}

Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by width and height.

For code example, see the documentation.

```python
def for_rendering_by_width_and_height(cls, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | `int` | The width of the output result (in pixels). |
| height | `int` | The height of the output result (in pixels). |

**Returns:** CadOptions: New instance of `CadOptions` class for rendering by width and height.

| Raises | Description |
| :- | :- |
| `ValueError` | If `height` is less than or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_width_and_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output.png")
        png_options.cad_options = CadOptions.for_rendering_by_width_and_height(1200, 800)
        viewer.view(png_options)
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
