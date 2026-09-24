---
title: VisioRenderingOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents options for rendering Visio documents."
type: docs
url: /python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Represents options for rendering Visio documents.

For details, see the documentation.

The VisioRenderingOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Initializes an instance of the [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | The figure width; height is calculated automatically. Default value is 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | The property renders only Visio figures, not a diagram. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Load Visio document
    with Viewer("map.vsdx") as viewer:
        # Convert the Visio file to PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Render only the master shapes.
        view_options.visio_rendering_options.render_figures_only = True
        # Specify shape width in pixels.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
