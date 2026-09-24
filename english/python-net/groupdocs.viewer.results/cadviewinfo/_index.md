---
title: CadViewInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents view information for CAD drawing."
type: docs
url: /python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Represents view information for CAD drawing.

The CadViewInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Initializes a new CadViewInfo instance. |

### Methods
| Method | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returns a string that represents the current object. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properties
| Property | Description |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | The list of layers contained by the CAD drawing. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | The list of layouts contained by the CAD drawing. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | The type of the file. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | The list of pages to view. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Example

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
Task guides that use `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### See Also
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
