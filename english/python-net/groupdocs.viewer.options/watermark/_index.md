---
title: Watermark class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents a text watermark."
type: docs
url: /python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Represents a text watermark.

For details, see the documentation.

The Watermark type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Initializes a Watermark instance. |

### Properties
| Property | Description |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | The watermark color. Default value is `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | The font name used for the watermark. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | The watermark position. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | The watermark size. Default value is [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | The watermark text. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    with Viewer("sample.docx") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark_{0}.html"
        )
        view_options.watermark = Watermark("This is a watermark")
        viewer.view(view_options)
```

### Guides
Task guides that use `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
