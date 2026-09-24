---
title: for_rendering_by_scale_factor method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a CadOptions instance for rendering by scale factor."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Initializes a CadOptions instance for rendering by scale factor.

For code example, see the documentation.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| scale_factor | `float` | Value higher than 1 enlarges output result; value between 0 and 1 reduces output result. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `scale_factor` is less or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
