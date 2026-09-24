---
title: CadOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The options for rendering CAD drawings."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

The options for rendering CAD drawings.

For more information and code examples, see the Render CAD drawings and models as HTML, PDF, and image files and Specify rendering options for CAD files documentation.

The CadOptions type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Initializes a CadOptions instance for rendering by height. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Initializes a CadOptions instance for rendering by scale factor. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by width. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Initializes an instance of the CadOptions class for rendering by width and height. |

### Properties
| Property | Description |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | The image background color. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | The flag that enables a performance-oriented conversion mode for all CAD formats, where setting it to True speeds up conversion at the cost of reduced output quality; defaults to False for maximum quality. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | The height of the output result (in pixels). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | The CAD drawing layers to render. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | The name of the specific layout to render. Layout name is case-sensitive. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | The PC3 plotter configuration file. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | The flag indicating whether layouts from the CAD document should be rendered. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | The scale factor. Value higher than 1 enlarges output result; value between 0 and 1 reduces output result. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | The drawing regions to render. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | The width of the output result (in pixels). |

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
        # Render by width and enable performance mode
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
