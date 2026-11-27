---
title: for_rendering_by_scale_factor method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the CadOptions class for rendering by scale factor."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by scale factor.

For a usage example, see the documentation.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| scale_factor | `float` | Value higher than 1 enlarges output result; value between 0 and 1 reduces output result. |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by scale factor.

| Raises | Description |
| :- | :- |
| `ValueError` | When `scale_factor` is less or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    # Load CAD file
    with Viewer("sample.dwg") as viewer:
        # Convert the diagram to PNG.
        png_options = PngViewOptions("set_image_size/image_with_size_limits.png")
        # Specify a scale factor.
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
